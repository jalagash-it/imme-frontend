<template>
  <b-container fluid class="ind">
    <b-row>
      <b-col>
        <h1>Индивидуальный пошив</h1>
      </b-col>
    </b-row>
    <b-row class="b-row">
      <b-col cols="6">
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований. В
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
    <b-row>
      <b-col>
        <img src="../assets/img/about-num.png" alt="" />
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований. В
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
          принимать собственные решения касаемо первоочередных требований. В
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
      <b-col cols="6" >
        <h1 class=" ">Оставьте заявку</h1>
        <p class="form-text">
          Сложно сказать, почему диаграммы связей представляют собой <br />
          не что иное, как квинтэссенцию победы маркетинга над разумом <br />
          и должны быть описаны максимально подробно.
        </p>
      </b-col>
      <b-col cols="6"  class="d-flex justify-content-end" >
        <b-form-group class="form__group">
          <b-form-input class="form-inputs" type="search" placeholder="Имя"></b-form-input>
          <b-form-input class="form-inputs" type="search" placeholder="E-mail*"></b-form-input>

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
          <b-button class="form-btn" variant="outline-primary">Подписаться</b-button>
         </div>
        </b-form-group>
      </b-col>
    </b-row>
  </b-container>
</template>
<style scoped>
.ind {
  background: #f7f9fc;
  font-family: "Montserrat";
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
  max-width:446px ;
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
 
.wrap{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.wrap .form-btn{
  font-style: normal;
font-weight: bold;
font-size: 16px;
line-height: 25px;
 
padding: 14px 48px;
 
width: 230px;
height: 53px;
 
 
border: 2px solid #FFFFFF;
box-sizing: border-box;
border-radius: 12px;

color: #FFFFFF;
}
</style>