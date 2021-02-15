<template>
  <b-container fluid>
    <section class="contacts">
      <h1 class="contacts__title">Контакты</h1>
      <div class="contacts__inner">
        <div class="contacts__info">
          <h2 class="contacts__info-title">
            Общество с ограниченной <br />
            ответственность «Фея»
          </h2>
          <a href="#!" class="contacts__info-props">Наши реквизиты </a
          ><img src="../assets/img/props__icon.png" alt="" />

          <div class="contact__info-phone">
            <span>Телефон:</span>
            <a href="tel:+88002018847">
              8 800 201 88 47
              <p class="contacts__info-time">в будние дни с 09:00 до 20:00</p>
            </a>
          </div>
          <div class="contact__info-email">
            <span>Email:</span>
            <a href="mailto:feya-kids@yandex.ru">feya-kids@yandex.ru</a>
          </div>
          <div class="contact__info-social">
            <span>Социалные сети:</span>
            <a href="#!"> <img src="../assets/img/vk.svg" alt="" /></a>
            <a href="#!"> <img src="../assets/img/facebook.svg" alt="" /></a>
            <a href="#!"> <img src="../assets/img/instagram.svg" alt="" /></a>
            <a href="#!"> <img src="../assets/img/ok.svg" alt="" /></a>
          </div>
        </div>

        <div class="contacts__map">
          <img src="../assets/img/map.png" alt="" />
        </div>
      </div>
      <div class="contacts__text">
        <p>
          Но граница обучения кадров однозначно фиксирует необходимость
          существующих финансовых и административных условий. Идейные
          соображения высшего порядка, а также повышение уровня гражданского
          сознания однозначно определяет каждого участника как способного
          принимать собственные решения касаемо первоочередных требований. <br>  <br> В
          частности, семантический разбор внешних противодействий выявляет
          срочную потребность экспериментов, поражающих по своей масштабности и
          грандиозности. Сложно сказать, почему диаграммы связей представляют
          собой не что иное, как квинтэссенцию победы маркетинга над разумом и
          должны быть описаны максимально подробно. Не следует, однако,
          забывать, что повышение уровня гражданского сознания не даёт нам иного
          выбора, кроме определения кластеризации усилий!
        </p>
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
      </div>
    </section>
  </b-container>
</template>

<style scoped>
.contacts {
  background: #f7f9fc;
  font-family: "Montserrat";
  padding: 0 15px;
}
.contacts__title {
  font-style: normal;
  font-weight: bold;
  font-size: 42px;
  line-height: 51px;
  display: flex;
  align-items: center;
  margin-bottom: 80px;

  /* color/dark */

  color: #151632;
}
.contacts__inner {
  display: flex;
  justify-content: space-around;
}
.contacts__info {
  flex-grow: 2;
  margin-right: 40px;
}
.contacts__info-title {
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;

  color: #151632;
}
.contacts__info-props {
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  margin-right: 5px;

  line-height: 22px;
  text-decoration: underline;

  color: #426cbe;
}
.contact__info-phone {
  display: flex;
  justify-content: space-between;
  margin-top: 86px;
}
.contact__info-phone a {
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;
  /* identical to box height, or 137% */

  /* color/dark */

  color: #151632;
}
.contact__info-email {
  display: flex;
  align-items: center;

  margin-bottom: 28px;
}
.contact__info-email a {
  margin-left: 150px;
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;

  color: #151632;
}
.contact__info-social {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.contact__info-social span {
}
.contact__info-social img {
}
.contacts__info span {
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 22px;
  /* identical to box height, or 157% */

  /* color/grey2 */

  color: #8889b3;
}

.contacts__info-time {
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 22px;
  /* identical to box height, or 157% */

  /* color/grey2 */

  color: #8889b3;
}
.contacts__map {
}
.contacts__text{
  display: flex; 
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 24px;
margin-top: 80px;
padding-bottom: 80px;
 

color: #60617B;
}
.contacts__text p{
  padding: 0 15px;

}
</style>