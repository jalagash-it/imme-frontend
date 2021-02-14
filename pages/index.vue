<template>
  <b-container fluid>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">NavBar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav class="main-nav">
        <b-navbar-nav align="left">start</b-navbar-nav>
        <b-navbar-nav align="center">center</b-navbar-nav>
        <b-navbar-nav align="right">end</b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <div class="catalog">
      <div class="catalog__content">
        <div class="left__arrow">
          <a href="#" class="img">prev</a>
        </div>
        <div class="catalog__item">
          <!-- <img src="../assets/img/1.jpg" alt="" /> -->
          <p>Бортики</p>
          <a href="#">Перейти</a>
        </div>

        <div class="catalog__item">
          <p>Балдахины</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <p>Коконы</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <p>Конверт</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <p>Косички</p>
          <a href="#">Перейти</a>
        </div>
        <div class="catalog__item">
          <p>Постельное белье</p>
          <a href="#">Перейти</a>
        </div>
        <div class="right__arrow">
          <a href="#"><img src="" alt="" />next</a>
        </div>
      </div>
    </div>
  </b-container>
</template>
 <script>
  
</script>

<style scoped>
.container-fluid {
  padding: 0;
  margin: 0;
}
.main-nav {
  display: flex;
  justify-content: space-between;
}
 
img{
  max-width: 100%;
  height: auto;
}
.catalog {
  margin-top: 55px;
  margin-bottom: 55px;
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
  border-radius: 30px;
  box-shadow: 5px 5px 30px rgba(41, 41, 167, 0.12);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-end;
  border: 3px solid #fff;

  background: linear-gradient(
    180deg,
    rgba(203, 191, 255, 0.2) 0%,
    rgba(203, 191, 255, 0) 100%, url('../assets/img/1.jpg')
  );
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
  font-size: 11px;
  line-height: 13px;
  margin-bottom: 10px;
}
.catalog__item a::after {
  content: ">";
}
</style>

 