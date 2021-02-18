<template>
  <b-container fluid class="customer">
    <b-row>
      <b-col>
        <h1 class="customer__title">Оптовым клиентам</h1>
        <b-breadcrumb :items="items"></b-breadcrumb
      ></b-col>
    </b-row>
    <b-row class="customer__content"  align-v="start" >
      <b-col cols="6">
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований.
          <br />
          <br />
          В частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
        </p>
      </b-col>
      <b-col cols="5" class="ml-auto customer__content-feedback"  >
        <h2>Какой-то текст-побуждение к регистрации <br> в Личном кабинете</h2>
        <a href="#!">Зарегистрироваться</a>
        <a href="#!"  class="feedback-signin"><img src="../assets/img/signin.png" alt=""></a>
      </b-col>
    </b-row>
    <b-row class="customer__img d-flex justify-content-center">
      <b-col cols="10">
        <img src="../assets/img/about-num.png" alt="" />
      </b-col>
    </b-row>
    <b-row class="customer__content">
      <b-col>
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований.
          <br />
          <br />
          В частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
        </p>
      </b-col>
      <b-col>
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований.
          <br />
          <br />
          В частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
        </p>
      </b-col>
    </b-row>
    <b-row class="customer__content d-flex align-items-start">
      <b-col cols="6">
        <img src="../assets/img/video.png" alt="" />
      </b-col>
      <b-col cols="6">
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований.
          <br />
          <br />
          В частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
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
          href: "#",
        },

        {
          text: "Оптовым клиентам",
          active: true,
        },
      ],
    };
  },
};
</script>
<style scoped>
.breadcrumb {
  background-color: #f7f9fc;
  margin-bottom: 48px;
}
.breadcrumb-item + .breadcrumb-item::before {
  content: "";
  /* background: url("../assets/img/ellipse.png"); */
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

.customer {
  background: #f7f9fc;
  font-family: "Montserrat";
}
.customer__title {
  font-style: normal;
  font-weight: bold;
  font-size: 42px;
  line-height: 51px;
  display: flex;
  align-items: center;

  margin-top: 48px;
  color: #151632;
}
.customer__content {
  margin-bottom: 80px;
  display: flex;
  align-items: flex-start;
   
}
.customer__content:last-child {
  padding-bottom: 80px;
  margin-bottom: 0;
}
.customer__content-feedback {
  width: 532px;
  height: 401px;
 
  background: url("../assets/img/feedback.png") no-repeat center center / contain;
  filter: drop-shadow(5px 5px 30px rgba(41, 41, 167, 0.12));
  border-radius: 15px;
  display: flex;
  flex-direction: column;
 
 
 
}
.customer__content-feedback h2 {
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  padding: 50px 50px 17px 50px;
  
  color: #151632;
}
.customer__content-feedback a {
  font-style: normal;
  font-weight: 500;
  font-size: 13px;
  line-height: 16px;
  margin-left: 50px;
  margin-bottom: 118px;
 
  color: #426cbe;
}
.feedback-signin img{
  width: 82px;
  height: 82px;

}
.customer__content p {
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 24px;

  color: #60617b;
}
.customer__img {
  margin: 80px 0;
  width: 100%;
}
img {
  width: 100%;
  height: auto;
}
</style>