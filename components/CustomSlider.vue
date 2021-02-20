<template>
  <section>
    <div class="header">
      <div class="title">
        <h1>Акции и скидки</h1>
        <span>(17)</span>
      </div>
      <div class="show-all">
        <a href="#">смотреть все</a>
      </div>
    </div>
    <div class="swiper-container">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
          <div class="slide__item">
            <p>Бортики</p>
            <a href="#">Перейти!!!</a>
          </div>
        </div>
      </div>
      <div class="swiper-button-prev">
        <img src="../assets/img/prev.png" alt="" />
      </div>

      <div class="swiper-button-next">
        <img src="../assets/img/next.png" alt="" />
      </div>
    </div>
  </section>
</template>
<script>
import SwiperCore, { Navigation } from "swiper";
import { Swiper, SwiperSlide } from "swiper/vue";

import "swiper/swiper-bundle.css";

SwiperCore.use([Navigation]);
export default {
  data() {
    return {
      slidesList: [
        { id: 1, img: "~assets/img/Rectangle 61.png" },
        { id: 2, img: "~assets/img/Rectangle 61.png" },
        { id: 3, img: "~assets/img/Rectangle 61.png" },
        { id: 4, img: "~assets/img/Rectangle 61.png" },
        { id: 5, img: "~assets/img/Rectangle 61.png" },
      ],
    };
  },
  components: {
    Swiper,
    SwiperSlide,
  },
  mounted() {
    new SwiperCore(".swiper-container", {
      slidesPerView: 4,
      spaceBetween: 10,

      // centerInsufficientSlides: true,

      loop: false,
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

.swiper-button-prev {
  left: 35px;
}
.swiper-button-next {
  right: 35px;
}

.slide__item {
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

.slide__item {
  background: url("../assets/img/2.png") no-repeat center center / cover;
}
.slide__item p {
  color: #60617b;
  font-family: "Montserrat", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 17px;
}
.slide__item a {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 500;

  line-height: 13px;
  margin-bottom: 10px;
}

.slide__item a::after {
  content: ">";
}
</style>