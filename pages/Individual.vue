<template>
  <b-container fluid class="ind">
    <b-row>
      <b-col>
        <h1 class="ind__title">Индивидуальный пошив</h1>
        <b-breadcrumb :items="items"></b-breadcrumb
      ></b-col>
    </b-row>
    <b-row class="ind__text" >
      <b-col cols="6">
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований. <br> <br> В
          частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
        </p>
      </b-col>
      <b-col cols="6">
        <img src="../assets/img/individual.png" alt="" />
      </b-col>
    </b-row>
    <b-row class="ind__img">
      <b-col>
        <img src="../assets/img/about-num.png" alt="" />
      </b-col>
    </b-row>
    <b-row class="ind__text">
      <b-col>
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований. <br> <br> В
          частности, семантический разбор внешних противодействий выявляет
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
          принимать собственные решения касаемо первоочередных требований. <br> <br> В
          частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
        </p>
      </b-col>
    </b-row>
    <b-row class="form d-flex align-items-center justify-content-between">
      <b-col cols="6">
        <h1 class=" ">Оставьте заявку</h1>
        <p class="form-text">
          Сложно сказать, почему диаграммы связей представляют собой <br />
          не что иное, как квинтэссенцию победы маркетинга над разумом <br />
          и должны быть описаны максимально подробно.
        </p>
      </b-col>
      <b-col cols="6" class="d-flex justify-content-end">
        <b-form-group class="form__group">
          <b-form-input
            class="form-inputs"
            type="search"
            placeholder="Имя"
          ></b-form-input>
          <b-form-input
            class="form-inputs"
            type="search"
            placeholder="E-mail*"
          ></b-form-input>

          <div class="wrap">
            <b-form-checkbox
              class="form-checkbox"
              id="checkbox-1"
              v-model="status"
              name="checkbox-1"
              value="accepted"
              unchecked-value="not_accepted"
            >
              Согласен с условиями <br />
              обработки Персональных <br />
              данных
            </b-form-checkbox>
            <b-button class="form-btn" variant="outline-primary"
              >Подписаться</b-button
            >
          </div>
        </b-form-group>
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
          text: "Индивидуальный пошив",
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
  /* content: "";
  background: url("../assets/img/ellipse.png"); */
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

.ind {
  background: #f7f9fc;
  font-family: "Montserrat";
}
.ind__title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: bold;
  font-size: 42px;
  line-height: 51px;
  display: flex;
  align-items: center;

  margin-top: 48px;
  color: #151632;
}
.ind__text {
  margin-bottom: 80px;
}
.ind__text p{
  font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 24px;
 

color: #60617B;
}
.ind__img {
  margin: 80px 0;
}
img {
  width: 100%;
  height: auto;
}
.form {
  height: 389px;
  background: url("../assets/img/in-form.png") no-repeat center center / cover;
  margin: 80px 0.075rem;
  color: #ffffff;
  border-radius: 30px;
  padding: 0 74px;
}
.form-title {
  font-style: normal;
  font-weight: bold;
  font-size: 32px;
  line-height: 39px;
  margin-bottom: 32px !important;
}
.form-text {
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
}
.form__group {
  max-width: 446px;
}
.form-inputs {
  background: rgba(255, 255, 255, 0.2);
  border-radius: 8px;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 17px;
  height: 50px;
  width: 446px;
  color: #ffffff;
  margin-bottom: 16px;
  border: none;
}
.form-inputs::placeholder {
  color: #fff;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 17px;
}
.form-checkbox {
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 15px;
}

.wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.wrap .form-btn {
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 25px;

  padding: 14px 48px;

  width: 230px;
  height: 53px;

  border: 2px solid #ffffff;
  box-sizing: border-box;
  border-radius: 12px;

  color: #ffffff;
}
</style>