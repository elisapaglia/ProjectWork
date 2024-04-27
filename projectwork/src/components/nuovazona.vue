

<template>

    
    <div id="testimonial">
        <hr>
        <h6 class="text-center pb-4 text-uppercase">what clients say</h6>
        <h2 class="text-center pb-5">Testimonial</h2>
        <div class="areaSConteiner">
            <div class="areaSlide ">
                <!--slider-->

     
                    <div id="testimonial">
                        <div v-for="(slide, index) in slides" v-show="index === currentIndex"  :key="slide.id"  class="">

                        
                        
                        <div class="slide active  ">
                            <div class="slider-containerMod slider-container d-flex">
                                <div class=" sliderMod slider d-flex  ">
                                    <!--first slide-->


 
   





                                    <div class="container mt-5 ">
                                        <div class="row rowPrimo">
                                            <div class="col-md-5 ">
                                                <div class=" ">
                                                    <!-- Colonna sinistra divisa in due righe --><!--card with image-->
                                                    <div class=" cardDestraDimesione card1 text-center p-4 ">

                                                        
                                                        <div class=" contenitoreImgModifiche ">
                                                            <img :src="slide.img"
                                                                style=" border-radius: 20px;"
                                                                class="imgModifiche card-img-top mx-auto mt-4"
                                                                :alt="slide.name">
                                                        </div>




                                                        <div class="card-body text-start ms-3 mt-3">
                                                            <span class="text-uppercase">rainbow-themes</span>
                                                            <h3> {{ slide.name }}</h3>
                                                            <h6>{{ slide.role }}</h6>
                                                        </div>
                                                    </div>



                                                </div>
                                            </div>
                                            <div class="col-md-7">


                                                <!-- Colonna destra divisa in due righe -->
                                                <div class="row ">
                                                    <div class="col-12 ">
                                                        <div class="p-3  ">
                                                            <!-- Riga Superiore destra | serve per creare spazio -->
                                                        </div>
                                                    </div>
                                                    <div class="col-12 ">
                                                        <div class="p-2  ">
                                                            <!-- Riga Inferiore destra -->
                                                            <div style="height: 40px;"></div>

                                                            <!--card with text-->
                                                            <div class="w-50 ">


                                                            </div>

                                                            <!--text-->
                                                            <div class="mt-5 " id="presentation">
                                                                <div class="d-flex flex-nowrap w-100 p-3">
                                                                    <div class="d-inline-block mt-3 pt-2 ps-3 ">
                                                                        <h4 class="fs-2 fw-bold text-start pr-3s">
                                                                            {{ slide.project }}
                                                                        </h4>
                                                                        <h6 class="lh-base text-start">  {{ slide.project }}</h6>
                                                                    </div>
                                                                    <div class="rating text-nowrap " id="stars">
                                                                        <i class="fa fa-star" aria-hidden="true"></i>
                                                                        <i class="fa fa-star" aria-hidden="true"></i>
                                                                        <i class="fa fa-star" aria-hidden="true"></i>
                                                                        <i class="fa fa-star" aria-hidden="true"></i>
                                                                        <i class="fa fa-star" aria-hidden="true"></i>
                                                                    </div>
                                                                </div>
                                                                <hr class="mx-auto ">
                                                                <p class="p-3 text-start"> {{ slide.testimonial }}</p>
                                                            </div>



                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>    
            </div>
        </div>
    </div></div>



    <!-- Bottoni -->
    <button @click="prevSlide" :disabled="sliding"><i class="fas fa-arrow-left"></i></button>
<button @click="nextSlide" :disabled="sliding"><i class="fas fa-arrow-right"></i></button>


    <!-- Dot -->
    <br>
    <div class="">
        <span v-for="(slide, index) in slides" :key="index" class="dot-a" :class="{ 'active': currentIndex === index }"
            @click="setCurrentIndex(index)"></span>
    </div>
    <br>
    <div>
        Valore attuale di currentIndex: {{ currentIndex }}
    </div>
    <br>




</template>

<script>
//NUOVO:




export default {
    name: 'TestimonialComponent',



    data() {
        return {
            currentIndex: 0,  // Index della slide attuale
            slides: [
                {
                    id: 1,
                    img: require("@/assets/final-home--1st.png"),
                    name: "Nevine Acotanza",
                    azienda: "Raibow theme",
                    role: "Chief Operating Officer",
                    project: "Android App Development",
                    period: "Upwork - Mar 4, 2015 - Aug 30, 2021",
                    testimonial: "Maecenas finibus nec sem ut imperdiet. Ut tincidunt est ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in, lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales phasellus smauris."
                },
                {
                    id: 2,
                    img: require("@/assets/final-home--2nd.png"),
                    azienda: "bound-trolola",
                    name: "Jone Duone Joe ",
                    role: "Operating Officer",
                    project: "WebAndroid App Development",
                    period: "Upwork - Mar 4, 2015 - Aug 30, 2021",
                    testimonial: "Maecenas finibus nec sem ut imperdiet. Ut tincidunt est ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in, lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales phasellus smauris."
                },

                {
                    id: 3,
                    img: require("@/assets/final-home--3rd.png"),
                    name: "Nevine Acotanza",
                    azienda: "glassfisom",
                    role: "Android App Design",
                    project: "Android App Development",
                    period: "Fiver - Mar 4, 2015 - Aug 30, 2021",
                    testimonial: "Maecenas finibus nec sem ut imperdiet. Ut tincidunt est ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in, lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales phasellus smauris."
                },
                {
                    id: 4,
                    img: require("@/assets/final-home--4th.png"),
                    name: "Mevine Thoda",
                    azienda: "ncd - design",
                    role: "Marketing Office",
                    project: "CEO - Marketing",
                    period: "Thoda Department - Mar 4, 2018 - Aug 30, 2021",
                    testimonial: "Maecenas finibus nec sem ut imperdiet. Ut tincidunt est ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in, lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales phasellus smauris."
                },
                {
                    id: 5,
                    img: require ("@/assets/final-home--5th.png"),
                    name: "Davei Luace",
                    azienda: "default name",
                    role: "Chief Operating Manager",
                    project: "Android App Development",
                    period: "via Upwork - Mar 4, 2015 - Aug 30, 2021",
                    testimonial: "Maecenas finibus nec sem ut imperdiet. Ut tincidunt est ac dolor aliquam sodales. Phasellus sed mauris hendrerit, laoreet sem in, lobortis mauris hendrerit andte. Ut tincidunt est ac dolor aliquam sodales phasellus smauris."
                },

            ],
            settings: [
                {
                    dots: true,
                    infinite: true,
                    speed: 500,
                    slidesToShow: 1,
                    slidesToScroll: 1,
                    prevArrow: '<button @click="prevSlide" class="btnn"><i class="fas fa-arrow-left"></i></button>',
                    nextArrow: '<button @click="nextSlide" class="btnn"><i class="fas fa-arrow-right"></i></button>'

                }

            ],
            sliding: false,
        };
    },
    setup() {
      const onSwiper = (swiper) => {
        console.log(swiper);
      };
      const onSlideChange = () => {
        console.log('slide change');
      };
      return {
        onSwiper,
        onSlideChange,
      };
    },
    mounted() {
        console.log('Current Index on mounted:', this.currentIndex); // Controlla il valore iniziale
    },
    methods: {
        nextSlide() {
        if (this.currentIndex < this.slides.length - 1) {
            this.currentIndex++;
        } else {
            this.currentIndex = 0;
        }

    },
    prevSlide() {
        if (this.currentIndex > 0) {
            this.currentIndex--;
        } else {
            this.currentIndex = this.slides.length - 1;
        }

    },
    setCurrentIndex(index) {
        this.currentIndex = index;

    },

    }
}
</script>


<style scoped>
/*Nuovo codice:inzio*/
.row {
    margin-bottom: 10px;
}

.areaSlide {
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    align-items: center;

}

.areaSConteiner {
    height: 100%;
    width: 100%;
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;


}


.bColor {
    background-color: #212529;
}



.btnn {
    width: 60px;
    height: 40px;
    margin: 4px;
    background-color: #262a2e;
    align-items: center;
    justify-content: center;

}

.bi {
    font-size: 20px;
    color: #ffffff;
    align-items: center;
    justify-content: center;
}

.bi:hover {
    font-size: 20px;
    color: #ffffff;
    align-items: center;
    justify-content: center;
}

.dot-a {
    height: 15px;
    width: 15px;
    margin: 0 5px;
    background-color: #bbb;
    border-radius: 50%;
    display: inline-block;
    background-color: #717171;

}

.dot-a.active {
    background-color: #ff014f;
}




.cardDestraDimesione {
    margin-top: 50px;
    max-height: 540px;
    border-radius: 20px;
    min-height: 520px;


}



.cardDestraModifiche {
    max-height: 600px;
    border-radius: 10px;
    max-width: 250px;
    text-align: center;
    border-radius: 20px;
}

.contenitoreImgModifiche {
    border-radius: 20px;
    height: 150%;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    position: relative;
}

.imgModifiche {
    border-radius: 20px;
    width: 100%;
    height: 150%;
    object-fit: contain;
    transition: transform 0.3s;

}

.imgModifiche:hover {
    border-radius: 20px;

}

.contenitoreImgModifiche:hover .imgModifiche {
    transform: scale(1.1);
}




.slider-containerMod {
    position: relative;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;




}

.sliderMod {
    display: flex !important;
    flex-wrap: nowrap !important;


}

.row-extended {
    width: 110%;
    /* O qualunque percentuale desiderata */
    margin: 0 -5%;
    /* Aggiusta i margini per centrare se estesa oltre 100% */
    overflow-x: hidden;
    /* Previene lo scroll orizzontale indesiderato */

}



.rating .fa-star {
    color: gold;
    /*colore delle stelle */
    margin: 0 2px;
    font-size: 7px;

}

#stars {
    border-radius: 6px;
    box-shadow: 10px 10px 19px #1c1e22, -10px -10px 19px #262a2e;
    max-height: 40px;

    vertical-align: middle;
    display: inline-flex;
    align-items: center;
}

.card1 {
    height: 100%;

}


/* Vecchio codice:*/
/* Vecchio codice:*/
/* Vecchio codice:*/
/* Vecchio codice:*/
/* Vecchio codice:*/
/* Vecchio codice:*/





* {
    background-color: #212529;
    margin-top: 0;
    color: #c4cfde;
}

#testimonial {
    padding-bottom: 100px;
    ;
}

hr {
    color: black;
    align-items: center;
    margin-top: 0;
    margin-left: 15px;
    margin-right: 15px;
}

h6 {
    color: #ff014f;
    padding-top: 20px;

}

h2 {
    font-family: 'Montserrat', sans serif;
    font-size: 60px;
    font-weight: 700;
    color: #c4cfde;
}

.slider-container {
    position: relative;
    overflow: hidden;
}

.slider {
    width: 70%;

}

.slide {
    min-width: 100%;
    display: none;
}

.slide.active {
    display: block;
}

.dot-container {
    position: absolute;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
}

.dot {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: 1px 4px 2px -3px rgba(0, 0, 0, 0.7) inset, -1px -3px 3px -2px rgba(255, 255, 255, 0.2) inset;
    margin: 0 10px;
}

.dot.active {
    background-color: #ff014f;
}

.card1,
#presentation,
#presentation button {
    box-sizing: border-box;
    box-shadow: 10px 10px 19px #1c1e22, -10px -10px 19px #262a2e;
    /*modificare dimensioni card destra qui */

}

.img-wrapper {
    width: 100%;
    overflow: hidden;
    border-radius: 10px;
    margin-bottom: 27px;
}

.card-body span {
    color: #ff014f;
}

.card1 h6 {
    color: #c4cfde;
    font-size: 14px;
    font-weight: 400;
    padding-top: 1px;

}

#presentation {
    border-radius: 15px;
    padding-top: 25px;

    background-color: linear-gradient(145deg, #1e2024, #23272b);
    height: 440px;
    margin-bottom: 20px;
}

#bottoni-slider button {
    border-radius: 15px;
}

#bottoni-slider button svg {
    width: 30px;
    height: 30px;
    margin: 20px;
    fill: #c4cfde;
}

#presentation h6 {
    color: #c4cfde;
    font-size: 15px;
    font-weight: 600;

    padding-bottom: 20px;


}

p {
    font-size: 15px;
}
</style>