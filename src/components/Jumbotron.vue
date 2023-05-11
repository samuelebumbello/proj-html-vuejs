<script>
export default{
    name: 'Jumbotron',
}
</script>

<template>
    <div class="jumbotron d-flex justify-content-center align-items-center">
        <div class="cont-jumbo d-flex justify-content-center">
            <div class="cont-text-jumbo d-flex flex-column align-items-center justify-content-center py-5">
                <h1 class="text-white fw-bold">Untold Stories</h1>
                <h4 class="text-white">There is an untold story behind every favorite song.</h4>
                <div class="button-jumbo my-5">
                    <button class="first-button me-4 fw-bold">LATEST ALBUM</button>
                    <button class="second-button fw-bold">LIVE DATES</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../scss/main' as *;

.jumbotron{
    height: 100vh;
}
.cont-jumbo{
    min-height: 750px;
}

.cont-text-jumbo{
    h1{
        font-size: 150px;
    }
    h4{
        font-size: 1.8rem;
    }
    .button-jumbo{
        .first-button{
            color: $secondary-color;
            background-color: $primary-color;
            padding: 15px 55px;
            border: none;
            font-size: 20px;
            &:hover{
                color: black;
                background-color: $secondary-color;
            }
        }
        .second-button{
            color: $secondary-color;
            background-color: transparent;
            padding: 14px 55px;
            font-size: 20px;
            border: 1px solid white;
            &:hover{
                color: black;
                background-color: $secondary-color;
            }
        }

    }
}
</style>