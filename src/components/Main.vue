<script>
export default{
    name: 'Main',
}
</script>

<template>
    <main>
        <div class="separator"></div>
        <div class="cont">
            <div class="cont-text  d-flex flex-column justify-content-center align-items-center">
                <h1 class="text-white fw-bold">Music Is Life</h1>
                <div class="linee m-4"></div>
                <p class="text-secondary text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum laboriosam error perspiciatis cumque! Illo vel, delectus laudantium repudiandae natus consequatur!</p>
            </div>
        </div>
        <div class="cont-main">
            <div class="cont-text  d-flex flex-column justify-content-center align-items-center">
                <h1 class="text-white fw-bold">Latest Band News</h1>
                <div class="linee m-4"></div>
                <p class="text-secondary text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum laboriosam error perspiciatis cumque! Illo vel, delectus laudantium repudiandae natus consequatur!</p>
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
@use '../scss/main' as *;

.cont{
    background-color: $terziary-color;
    width: 100%;
    padding: 70px;
}
.cont-main{
    width: 100%;
    background-color: $quaternary-color;

}
.separator{
    margin: auto;
    width: 30%;
    border: 8px solid $primary-color;
}
.linee{
    width: 20%;
    border: 1px solid #7d7b8d25;
}
.text-white{
    font-size: 70px;
}
.text-secondary{
    width: 850px;
}


</style>