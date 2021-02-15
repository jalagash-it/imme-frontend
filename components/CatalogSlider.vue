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
            <!-- <img src="../assets/img/prev.png" alt="" /> -->
          </div>
          <div class="swiper-button-next">
            <!-- <img src="../assets/img/next.png" alt="" /> -->
          </div>
      </b-col>
    </b-row>
    <hr />
    <div class="catalog">
      <div class="catalog__content">
        <div class="catalog__item">
          <p>Балдахины</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <!-- <img src="../assets/img/3.png" alt="" /> -->
          <p>Коконы</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <!-- <img src="../assets/img/4.png" alt="" /> -->
          <p>Конверт</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <!-- <img src="../assets/img/5.png" alt="" /> -->
          <p>Косички</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <!-- <img src="../assets/img/6.png" alt="" /> -->
          <p>Постельное белье</p>
          <a href="#">Перейти</a>
        </div>
        <div class="right__arrow">
          <a href="#"><img src="../assets/img/next.png" alt="" /> </a>
        </div>
      </div></div
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
      loop: true,
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      },
    });
  },
};
</script>
<style lang="sass" scoped>
@import "swiper/swiper.scss"
@import "swiper/components/navigation/navigation.scss"
</style>
<style scoped>
/* .swiper-button-prev:after,
.swiper-button-next::after {
  content: "";
} */
/* .swiper-button-prev{
 background: url(../assets/img/prev.png); 
} */
.swiper-container {
  width: 100%;
  height: auto;
}
.swiper-wrapper {
  width: 80%;
}
.catalog {
  margin-top: 105px;
  margin-bottom: 55px;

  height: 536px;

  background: linear-gradient(180deg, #ffffff 0%, #f2f2ff 100%);
  background: url(../assets/img/bg.png) no-repeat center -55px / cover;
}

.catalog__content {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.left__arrow {
  text-align: center;
}
.right__arrow {
  text-align: center;
}
.catalog__item {
  position: relative;
  width: 193px;
  height: 319px;

  border: 4px solid #ffffff;

  border-radius: 30px;
  box-shadow: 5px 5px 30px rgba(41, 41, 167, 0.12);
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