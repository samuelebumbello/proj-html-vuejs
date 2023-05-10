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
                <!-- QUI BISOGNA CREARE L'OFF-CANVAS -->
                <span class="fs-2">
                    <i class="fa-solid fa-bars"></i>
                </span>  
            </div>
        </div>
    </header>
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
</style>