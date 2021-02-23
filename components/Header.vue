<template>
  <header>
    <b-container>
      <b-row>
        <b-col>
          <b-navbar toggleable="lg">
            <div class="row-1">
              <b-navbar-brand href="#"><brand /></b-navbar-brand>

              <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

              <b-collapse is-nav class="top-nav">
                <b-navbar-nav>
                  <div class="your-city">
                    <label for="yourCity">Ваш город</label>
                    <a href="#" id="yourCity">Владимир</a>
                  </div>
                  <social-medias />
                  <div>3</div>
                </b-navbar-nav>
              </b-collapse>
            </div>
            <div class="row-2">
              <b-collapse id="nav-collapse" is-nav class="main-nav">
                <b-navbar-nav>
                  <b-nav-item href="#">О компании</b-nav-item>
                  <b-nav-item href="#">Каталог</b-nav-item>
                  <b-nav-item href="#">Акции</b-nav-item>
                  <b-nav-item href="#">Новинки</b-nav-item>
                  <b-nav-item href="#">Оптовым клиентам</b-nav-item>
                  <b-nav-item href="#">Индивидуальный пошив</b-nav-item>
                  <b-nav-item href="#">Полезная информация</b-nav-item>
                  <b-nav-item href="#">Отзывы</b-nav-item>
                  <b-nav-item href="#">Контакты</b-nav-item>
                </b-navbar-nav>
              </b-collapse>
            </div>
          </b-navbar>
        </b-col>
      </b-row>
    </b-container>
  </header>
</template>

<style scoped lang="scss">

header {
  height: 800px;
  border: 1px solid black;
  background-image: url("~assets/img/img.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  .navbar {
    height: 124px;
    display: flex;
    flex-direction: column;
    .row-1 {
      display: flex;
      border: 1px solid red;
      height: 72px;
      margin-top: 8px;
      width: 100%;
      .navbar-nav {
        flex-grow: 1;
        display: flex;
        justify-content: space-between;
        .your-city {
          display: flex;
          flex-direction: column;
        }
      }
    }
    .row-2 {
      border: 1px solid green;
      width: 100%;
      height: 42px;
    }
    social-medias {
      height: 100%;
    }
  }
  .top-nav {
    display: flex;
    justify-content: space-between;
  }
}
</style>