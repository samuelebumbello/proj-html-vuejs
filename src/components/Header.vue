<script>
export default {
  name: 'Header',

}
</script>

<template>
    <header>
        <div class="container-header d-flex justify-content-between px-5 align-items-center">
            <div class="cont-img-head">
                <img src="../assets/img/avada-music-logo.png" alt="">
            </div>
            <div class="cont-offcanvas text-white">
                <span class="fs-2">
                    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#modalMenu">
                        <i class="fa-solid fa-bars"></i>
                    </button>
                </span> 
            </div>
        </div>
    </header>

    <div class="modal fade" id="modalMenu" tabindex="-1" aria-labelledby="modalMenuLabel" aria-hidden="true">
                    <div class="modal-dialog modal-fullscreen">
                        <div class="modal-content">
                            <div class="modal-header">
                                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                            </div>
                            <div class="modal-body d-flex justify-content-center flex-column align-items-center">
                                <ul>
                                    <li>
                                        <a class="text-white" href="">Home</a>
                                    </li>
                                </ul>
                                <ul>
                                    <li>
                                        <a href="">Meet The Band</a>
                                    </li>
                                </ul>
                                <ul>
                                    <li>
                                        <a href="">Live Dates</a>
                                    </li>
                                </ul>
                                <ul>
                                    <li>
                                        <a href="">Latest News</a>
                                    </li>
                                </ul>
                                <ul>
                                    <li>
                                        <a href="">Albumbs</a>
                                    </li>
                                </ul>
                                <ul>
                                    <li>
                                        <a href="">Fans</a>
                                    </li>
                                </ul>
                            </div>

                        </div>
                    </div>
                </div> 
</template>

<style lang="scss" scoped>
@use '../scss/main' as *;

.container-header{
    position: fixed;
    z-index: 999;
    height: 90px;
    width: 100%;
    background-color: transparent;

}

.btn-primary{
    background-color: transparent;
    border: 0;
    font-size: 32px;
    --bs-btn-active-bg: ;
    --bs-btn-active-border-color: ;
    &:hover{
        background-color: transparent;
        border: 0;
    }

}
.modal-header{
    border: 0;
}
.modal-content{
    background-color: $primary-color;
}

.modal-body{
    ul{
        margin-bottom: 36px;
        li{
            font-size: 37px;
            list-style: none;
            a{
                color: rgb(177, 177, 177);
                text-decoration: none;
            }
        }
    }
}


</style>