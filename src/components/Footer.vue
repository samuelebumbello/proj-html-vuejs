<script>
export default{
    name:'Footer',
}
</script>

<template>
    <footer>
        <div class="container-foot d-flex justify-content-between px-5 align-items-center">
            <div class="cont-img-foot">
                <img src="../assets/img/logo_footer.png" alt="">
            </div>
            <div class="cont-nav">
                <ul class="nav justify-content-end">
                    <li class="nav-item">
                        <a class="nav-link text-secondary" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-secondary" href="#">Meet The Band</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white active" href="#">Live Dates</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-secondary" href="#">Latest News</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-secondary" href="#">Albums</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-secondary" href="#">Fans</a>
                    </li>
                </ul> 
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../scss/main' as *;

.container-foot{
    height: 150px;
    width: 100%;
    background-color: $terziary-color;
}
.cont-nav{
    ul{
        font-size: 14px;
        li{
            a{
                margin: 12px;
                padding: 0;
                
            }
        }
    }
}

</style>