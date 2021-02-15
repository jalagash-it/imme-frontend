<template>
  <b-container fluid>
    <b-row>
      <b-col>
        <div class="swiper-container">
          <div class="swiper-wrapper">         
            <div class="swiper-slide">
              <div class="catalog__item">
                <p>Бортики</p>
                <a href="#">Перейти</a>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="catalog__item">
                <p>Бортики</p>
                <a href="#">Перейти</a>
              </div>
            </div>
             <div class="swiper-slide">
              <div class="catalog__item">
                <p>Бортики</p>
                <a href="#">Перейти</a>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="catalog__item">
                <p>Бортики</p>
                <a href="#">Перейти</a>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="catalog__item">
                <p>Бортики</p>
                <a href="#">Перейти</a>
              </div>
            </div>
             <div class="swiper-slide">
              <div class="catalog__item">
                <p>Бортики</p>
                <a href="#">Перейти</a>
              </div>
            </div>
           
            </div>
       
             
           
         
        </div>
    
             <div class="swiper-button-prev">
            <img src="../assets/img/prev.png" alt="" />
          </div>
          <div class="swiper-button-next">
            <img src="../assets/img/next.png" alt="" />
          </div>
      </b-col>
    </b-row>
    <hr />
  
  ></b-container>
</template>
<script>
import SwiperCore, { Navigation } from "swiper";
import { Swiper, SwiperSlide } from "swiper/vue";

import "swiper/swiper-bundle.css";

SwiperCore.use([Navigation]);
export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  mounted() {
    new SwiperCore(".swiper-container", {
      slidesPerView: 6,
      spaceBetween: 0,
      
      // centerInsufficientSlides: true,
      
      loop: true,
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      }
   
    });
  },
};
</script>
<style lang="sass" scoped>
@import "swiper/swiper.scss"
@import "swiper/components/navigation/navigation.scss"
</style>
<style scoped>
.swiper-button-prev:after,
.swiper-button-next::after {
  content: "";
}  
   
.swiper-container {
  width: 90%;
 
  height: auto;
   margin-top: 105px;
  margin-bottom: 55px;

 

 
   

}
 
.swiper-button-prev{
  left: 35px;
}
.swiper-button-next{
  right: 35px;
  
 
 
}
 
 
 
 
.catalog__item {
 
  width: 193px;
  height: 319px;

  border: 4px solid #ffffff;

  border-radius: 30px;
 
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-end;
}

.catalog__item {
  background: url("../assets/img/2.png") no-repeat center center / cover;
}
.catalog__item p {
  color: #60617b;
  font-family: "Montserrat", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 17px;
}
.catalog__item a {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 500;

  line-height: 13px;
  margin-bottom: 10px;
}

.catalog__item a::after {
  content: ">";
}
</style>