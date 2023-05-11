<script>
export default{
    name: 'Main',
}
</script>

<template>
    <main>
        <div class="cont">
            <div class="separator mb-5"></div>
            <div class="cont-text d-flex flex-column justify-content-center align-items-center">
                <h1 class="text-white fw-bold">Music Is Life</h1>
                <div class="linee m-4"></div>
                <p class="p-sec text-secondary text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum laboriosam error perspiciatis cumque! Illo vel, delectus laudantium repudiandae natus consequatur!</p>
            </div>
        </div>
        <div class="cont-main">
            <div class="cont-text  d-flex flex-column justify-content-center align-items-center">
                <h1 class="text-white fw-bold">Latest Band News</h1>
                <div class="linee m-4"></div>
                <p class="p-sec text-secondary text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum laboriosam error perspiciatis cumque! Illo vel, delectus laudantium repudiandae natus consequatur!</p>
            </div>
            
            <!-- CARDS -->
            <div class="container-fluid-fix">
                <div class="grid-container">

                    <div class="card card_1">
                        <img class="d-block" src="../assets/img/blog_music_techo-1200x600.jpg" alt="">
                        <div class="content">
                            <h3>Technology and music</h3>
                            <p class="text-secondary m-0">Sed sit amet semp turpis. Curabitur curcsus lacinia est at interdum risus id condimentum sit amet semp turpis sit amet semp turpis..</p>
                        </div>
                    </div>

                    <div class="card card_2">
                        <img class="d-block" src="../assets/img/blog-post1-600x900.jpg" alt="">
                        <div class="content">
                            <h3>Taking it back to the old school</h3>
                            <p class="text-secondary m-0">Sed sit amet semp turpis. Curabitur curcsus lacinia est at interdum risus id condimentum</p>
                        </div>
                    </div>

                    <div class="card card_3">
                        <img class="d-block" src="../assets/img/blog-post3-600x900.jpg" alt="">
                        <div class="content">
                            <h3>While my guitar gently weeps</h3>
                            <p class="text-secondary m-0">Sed sit amet semp turpis. Curabitur curcsus lacinia est at interdum risus id condimentum</p>
                        </div>
                    </div>

                    <div class="card card_4">
                        <img class="d-block" src="../assets/img/blog-post4-600x900.jpg" alt="">
                        <div class="content">
                            <h3>It just sounds better</h3>
                            <p class="text-secondary m-0">Sed sit amet semp turpis. Curabitur curcsus lacinia est at interdum risus id condimentum</p>
                        </div>
                    </div>

                    <div class="card card_5">
                        <img class="d-block" src="../assets/img/blog-post2-600x900.jpg" alt="">
                        <div class="content">
                            <h3>Sharing the stage with a legend</h3>
                            <p class="text-secondary m-0">Sed sit amet semp turpis. Curabitur curcsus lacinia est at interdum risus id condimentum</p>
                        </div>
                    </div>

                    <div class="card card_6">
                        <img class="d-block" src="../assets/img/blog_flavor_rock-1200x600.jpg" alt="">
                        <div class="content">
                            <h3>The flavor of rock</h3>
                            <p class="text-secondary m-0">Sed sit amet semp turpis. Curabitur curcsus lacinia est at interdum risus id condimentum</p>
                        </div>
                    </div>
                    
                </div>
            </div>
            <!-- FINE CARDS -->
        </div>
        






        <div class="news-container d-flex justify-content-center align-items-center">
            <div class="news-text">
                <a class="fw-bold" href="">VIEW ALL LATEST NEWS</a>
            </div>
        </div>
        <div class="main-jumbo d-flex justify-content-center align-items-center">
            <div class="song">
                <p class="text-white text-center">“I just listened to it and said to myself, “Man, I really love this album.” Still, today, it just sounds so fresh. It sounds full of ideas. These guys knew what they were doing. They’re good. And they’re inventive. I haven’t heard anything this year that’s as inventive. I don’t really expect to.”</p>

                <div class="modal-dialog modal-dialog-centered">
                    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <iframe width="500" height="300" src="https://www.youtube.com/embed/aL0dOoLpf7M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                            </div>
                        </div>
                    </div>
                </div>  

                <div class="button-yt d-flex justify-content-center mt-5">
                    <button class="btn-yt" data-bs-toggle="modal" data-bs-target="#exampleModal">
                            <img src="https://avada.website/music/wp-content/uploads/sites/68/2016/07/band_interview_play_icon.png"  alt="">
                    </button>
                </div>

            </div>
        </div>
            <div class="cont-prefoot">
                <div class="cont-text  d-flex flex-column justify-content-center align-items-center">
                    <h1 class="text-white fw-bold">Live Dates</h1>
                    <div class="linee m-4"></div>
                    <p class=" text-secondary text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum laboriosam error perspiciatis cumque! Illo vel, delectus laudantium repudiandae natus consequatur!</p>
                </div>
              
                <div class="accordion accordion-flush d-flex justify-content-center align-items-center flex-column" id="accordionFlushExample">

                    <!-- PRIMO ACCORDION -->
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingOne">
                            <button class="accordion-button collapsed fw-bold" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                                <i class="fa-solid fa-plus text-white me-4"></i>
                                17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
                            </button>
                        </h2>
                        <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body d-flex justify-content-between">
                                    <div class="left-body">
                                        <img src="https://map.viamichelin.com/map/carte?map=viamichelin&z=10&lat=45.47688&lon=9.22656&width=550&height=382&format=png&version=latest&layer=background&debug_pattern=.*" alt="">
                                    </div>
                                    <div class="right-body d-flex justify-content-between flex-column">
                                        <h4 class="text-white pt-4">Untold Stories</h4>
                                        <p class="text-secondary">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nemo harum neque iste dolores molestias perspiciatis maiores. Repellendus est eaque reiciendis voluptatum saepe a quia sequi id, quod voluptatibus! Repellat, veniam!</p>
                                        <div class="btn-body">
                                            <button class="fw-bold">
                                                <a href="">BOOK NOW</a>
                                            </button>
                                        </div>
                                    </div>
                            </div>
                        </div>
                    </div>

                    <!-- SECONDO ACCORDION -->
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingTwo">
                            <button class="accordion-button collapsed fw-bold" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                                <i class="fa-solid fa-plus text-white me-4"></i>
                                17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
                            </button>
                        </h2>
                        <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body d-flex justify-content-between">
                                <div class="left-body">
                                        <img src="https://map.viamichelin.com/map/carte?map=viamichelin&z=10&lat=45.47688&lon=9.22656&width=550&height=382&format=png&version=latest&layer=background&debug_pattern=.*" alt="">
                                </div>
                                <div class="right-body d-flex justify-content-between flex-column">
                                    <h4 class="text-white pt-4">Untold Stories</h4>
                                    <p class="text-secondary">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nemo harum neque iste dolores molestias perspiciatis maiores. Repellendus est eaque reiciendis voluptatum saepe a quia sequi id, quod voluptatibus! Repellat, veniam!</p>
                                    <div class="btn-body">
                                        <button class="fw-bold">
                                            <a href="">BOOK NOW</a>
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- TERZO ACCORDION -->
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingThree">
                            <button class="accordion-button collapsed fw-bold" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                                <i class="fa-solid fa-plus text-white me-4"></i>
                                17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
                            </button>
                        </h2>
                        <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body d-flex justify-content-between">
                                <div class="left-body">
                                        <img src="https://map.viamichelin.com/map/carte?map=viamichelin&z=10&lat=45.47688&lon=9.22656&width=550&height=382&format=png&version=latest&layer=background&debug_pattern=.*" alt="">
                                </div>
                                <div class="right-body d-flex justify-content-between flex-column">
                                    <h4 class="text-white pt-4">Untold Stories</h4>
                                    <p class="text-secondary">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nemo harum neque iste dolores molestias perspiciatis maiores. Repellendus est eaque reiciendis voluptatum saepe a quia sequi id, quod voluptatibus! Repellat, veniam!</p>
                                    <div class="btn-body">
                                        <button class="fw-bold">
                                            <a href="">BOOK NOW</a>
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- QUARTO ACCORDION -->
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingFour">
                            <button class="accordion-button collapsed fw-bold" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseFour" aria-expanded="false" aria-controls="flush-collapseFour">
                                <i class="fa-solid fa-plus text-white me-4"></i>
                                17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
                            </button>
                        </h2>
                        <div id="flush-collapseFour" class="accordion-collapse collapse" aria-labelledby="flush-headingFour" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body d-flex justify-content-between">
                                <div class="left-body">
                                        <img src="https://map.viamichelin.com/map/carte?map=viamichelin&z=10&lat=45.47688&lon=9.22656&width=550&height=382&format=png&version=latest&layer=background&debug_pattern=.*" alt="">
                                </div>
                                <div class="right-body d-flex justify-content-between flex-column">
                                    <h4 class="text-white pt-4">Untold Stories</h4>
                                    <p class="text-secondary">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nemo harum neque iste dolores molestias perspiciatis maiores. Repellendus est eaque reiciendis voluptatum saepe a quia sequi id, quod voluptatibus! Repellat, veniam!</p>
                                    <div class="btn-body">
                                        <button class="fw-bold">
                                            <a href="">BOOK NOW</a>
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- QUINTO ACCORDION -->
                    <div class="accordion-item">
                        <h2 class="accordion-header" id="flush-headingFive">
                            <button class="accordion-button collapsed fw-bold" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseFive" aria-expanded="false" aria-controls="flush-collapseFive">
                                <i class="fa-solid fa-plus text-white me-4"></i>
                                17/08/2020 GEM FESTIVAL 2020 ANAKALIA, GEORGIA
                            </button>
                        </h2>
                        <div id="flush-collapseFive" class="accordion-collapse collapse" aria-labelledby="flush-headingFive" data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body d-flex justify-content-between">
                                <div class="left-body">
                                        <img src="https://map.viamichelin.com/map/carte?map=viamichelin&z=10&lat=45.47688&lon=9.22656&width=550&height=382&format=png&version=latest&layer=background&debug_pattern=.*" alt="">
                                </div>
                                <div class="right-body d-flex justify-content-between flex-column">
                                    <h4 class="text-white pt-4">Untold Stories</h4>
                                    <p class="text-secondary">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nemo harum neque iste dolores molestias perspiciatis maiores. Repellendus est eaque reiciendis voluptatum saepe a quia sequi id, quod voluptatibus! Repellat, veniam!</p>
                                    <div class="btn-body">
                                        <button class="fw-bold">
                                            <a href="">BOOK NOW</a>
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>


                <div class="news-container d-flex justify-content-center align-items-center">
                    <div class="news-text">
                        <a class="fw-bold" href="">VIEW ALL LATEST NEWS</a>
                    </div>
                </div>
            </div>


    </main>
</template>

<style lang="scss" scoped>
@use '../scss/main' as *;

.container-fluid-fix {
    max-width: 1200px;
    margin: 0 auto;
}

.cont{
    background-color: $terziary-color;
    width: 100%;
    padding: 0px 70px 70px;
}

.cont-main{
    padding-top: 70px;
    width: 100%;
    background-color: $quaternary-color;

}
// CARDS //

.card_1 { grid-area: foto1; }
.card_2 { grid-area: foto2; }
.card_3 { grid-area: foto3; }
.card_4 { grid-area: foto4; }
.card_5 { grid-area: foto5; }
.card_6 { grid-area: foto6; }
.grid-container {
  display: grid;
  grid-template-areas:
    'foto1	foto1	foto1   foto1	foto2	foto2 '
    'foto3	foto3	foto4   foto4	foto2	foto2 '
    'foto3	foto3	foto4   foto4	foto5	foto5 '
    'foto6	foto6	foto6   foto6	foto5	foto5 ';
  gap: 30px;
  padding: 30px;
}


.container{
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fit,400px);
    place-content: center;
    gap: 2rem;
    padding-top: 60px;
    padding-bottom: 150px;
    border: none;
}
.card{
    position: relative;
    border: none;
    background-color: $quaternary-color;
    img{
        object-fit: cover;
    }
}
.content{
    position: absolute;
    bottom: 0;
    padding: 20px;
    background-color: $terziary-color;
    width: 100%;
    h3{
        font-weight: bold;
        font-size: 17px;
        color: $primary-color;
        line-height: 1.3rem;
    }
    p{
        font-size: 15px;
    }
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
    .p-sec{
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
            a{
                color: black;
            }
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
.cont-prefoot{
    width: 100%;
    background-color: $quaternary-color;
    padding-top: 5rem;
}

// ACCORDION //
.accordion-flush{
    padding-bottom: 8rem;
    padding-top: 2rem;
    width: 100%;
    .accordion-item{
        border: 0;
        margin-bottom: 10px;
        width: 60%;
        &:hover{
            background-color: #444E63;
        }
    }
}
.accordion-button{
    background-color: $terziary-color;
    &:focus{
        background-color: $terziary-color;
    }
    &::after{
        background-image: none;
    }
    i{
        background-color: $terziary-color;
        padding: 6px;
        font-size: 10px;
        transition: all 0.2s;
        &:hover{
            background-color: $primary-color;
        }
    }

}
.accordion-button[data-v-3fa90f43]:not(.collapsed){
    color: $primary-color;
    background-color: $terziary-color;
}
.accordion-button[data-v-3fa90f43]:focus{
    border-color: $terziary-color;
}
.accordion-body{
    background-color: $terziary-color;
    img{
        width: 330px;
    }
}
.accordion-header{

    button{
        font-size: 20px;
        color: $primary-color;
        background-color: $terziary-color;
    }
}

.right-body{
    padding-left: 50px;
    h4{
        font-size: 20px;
    }
    p{
        width: 100%;
        color: $terziary-color;
    }
}
.btn-body{
    button{
        background-color: $primary-color;
        border: 0;
        padding: 10px 25px;
        a{
            color: $secondary-color;
            text-decoration: none;
        }
        &:hover{
            background-color: $secondary-color;
            a{
                color: black;
            }
        }
    }
    
}
</style>