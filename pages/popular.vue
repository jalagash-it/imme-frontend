<template>
  <b-container fluid class="popular">
    <b-row>
      <b-col>
        <h1 class="popular-title">Популярное</h1>
        <b-breadcrumb :items="items"></b-breadcrumb
      ></b-col>
    </b-row>

    <b-row class="d-flex justify-content-center popular__items ">
      <b-card
        title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </b-card-text>

        <b-button href="#" variant="primary">Go somewhere</b-button>
      </b-card>
      <b-card
        title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </b-card-text>

        <b-button href="#" variant="primary">Go somewhere</b-button>
      </b-card>
      <b-card
        title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </b-card-text>

        <b-button href="#" variant="primary">Go somewhere</b-button>
      </b-card>
      <b-card
        title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem;"
        class="mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </b-card-text>

        <b-button href="#" variant="primary">Go somewhere</b-button>
      </b-card>
    </b-row>
  
    <b-row>
      <b-col><h1>SEO-блок</h1></b-col>
    </b-row>
    <b-row>
      <b-col cols="6">
        <img src="../assets/img/map.png" alt="" />

        <p>
          И нет сомнений, что явные признаки победы институционализации набирают
          популярность среди определенных слоев населения, а значит, должны быть
          своевременно верифицированы. Задача организации, в особенности же
          новая модель организационной деятельности предоставляет широкие
          возможности для прогресса профессионального сообщества. <br />
          <br />
          Также как социально-экономическое развитие говорит о возможностях
          новых принципов формирования материально-технической и кадровой базы.
        </p>
      </b-col>
      <b-col cols="6">
        <p>
          И нет сомнений, что явные признаки победы институционализации набирают
          популярность среди определенных слоев населения, а значит, должны быть
          своевременно верифицированы. Задача организации, в особенности же
          новая модель организационной деятельности предоставляет широкие
          возможности для прогресса профессионального сообщества. Также как
          социально-экономическое развитие говорит о возможностях новых
          принципов формирования материально-технической и кадровой базы. Задача
          организации, в особенности же новая модель организационной
          деятельности предоставляет широкие возможности для прогресса
          профессионального сообщества. Задача организации, в особенности же
          новая модель организационной деятельности предоставляет широкие
          возможности для прогресса профессионального сообщества.
        </p>
        <p>
          И нет сомнений, что явные признаки победы институционализации набирают
          популярность среди определенных слоев населения, а значит, должны быть
          своевременно верифицированы. Задача организации, в особенности же
          новая модель организационной деятельности предоставляет широкие
          возможности для прогресса профессионального сообщества. <br />
          <br />
          Также как социально-экономическое развитие говорит о возможностях
          новых принципов формирования материально-технической и кадровой базы.
        </p>
      </b-col>
    </b-row>
  </b-container>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          text: "Главная",
          href: "#"
        },

        {
          text: "Популярное",
          active: true
        }
      ]
    };
  }
};
</script>
<style scoped>
img {
  width: 100%;
  height: auto;
}
.breadcrumb {
  background-color: #f7f9fc;
  margin-bottom: 48px;
}
.breadcrumb-item + .breadcrumb-item::before {
  content: "";
  background: url("../assets/img/ellipse.png");
}
.breadcrumb a {
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 16px;

  color: #60617b;
}
.breadcrumb .active span {
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 16px;

  color: #9fa1cb;
}

.popular {
  background: #f7f9fc;
  font-family: "Montserrat";
  padding: 25px;

  font-family: "Montserrat";
}
.popular-title {
  font-style: normal;
  font-weight: bold;
  font-size: 42px;
  line-height: 51px;
  display: flex;
  align-items: center;
  padding-top: 48px;

  /* color/dark */

  color: #151632;
}
.popular__items {
  margin-bottom: 48px;
}
 
.mb-2{
  margin-right: 15px;
}
.mb-2:last-child{
  margin-right: 0;
}
</style>
