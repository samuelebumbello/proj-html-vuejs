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
        <div class="news-container d-flex justify-content-center align-items-center">
            <div class="news-text">
                <a class="fw-bold" href="">VIEW ALL LATEST NEWS</a>
            </div>
        </div>
        <div class="main-jumbo d-flex justify-content-center align-items-center">
            <div class="song">
                <p class="text-white text-center">“I just listened to it and said to myself, “Man, I really love this album.” Still, today, it just sounds so fresh. It sounds full of ideas. These guys knew what they were doing. They’re good. And they’re inventive. I haven’t heard anything this year that’s as inventive. I don’t really expect to.”</p>
                <div class="button-yt d-flex justify-content-center mt-5">
                    <button class="btn-yt">
                        <a href="https://www.youtube.com/watch?v=aL0dOoLpf7M">
                            <img src="https://avada.website/music/wp-content/uploads/sites/68/2016/07/band_interview_play_icon.png"  alt="">
                        </a>
                    </button>
                </div>
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
    height: 1000px;
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

.news-container{
    width: 100%;
    height: 160px;
    background-color: $primary-color;
    transition: all 0.3s;
    a{
        color: white;
        text-decoration: none;
        font-size: 20px;
    }
    &:hover{
            background-color: white;
            color: black;
        }
}

.main-jumbo{
    width: 100%;
    height: 100vh;
    background-image: url(../assets/img/home-testimonial-parallax.jpg);
    .song{
        width: 50%;
        p{
            font-size: 25px;
            line-height: 44px;
            letter-spacing: 2px;
        }
        .btn-yt{
            background-color: transparent;
            border: 0;
        }
    }
}


</style>