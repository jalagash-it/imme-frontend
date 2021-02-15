<template>
  <b-container fluid> <div class="catalog">
    <div class="catalog__content">
      <div class="left__arrow">
        <a href="#"> <img src="../assets/img/prev.png" alt="" /></a>
      </div>
      <div class="catalog__item">
        <p>Бортики</p>
        <a href="#">Перейти</a>
      </div>

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
    </div>
  </div></b-container>
  
</template>

<style scoped>
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