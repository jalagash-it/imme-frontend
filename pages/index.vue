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
        <a href="#"><img src="" alt="">next</a>
      </div>
      </div>

    </div>
  </b-container>
</template>

<script>
export default {};
</script>

<style scoped>
 
@import url("../assets/css/main.css");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap");
.container-fluid {
  padding: 0;
  margin: 0;
}
.main-nav {
  display: flex;
  justify-content: space-between;
}

</style>