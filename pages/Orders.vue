<template>
  <section>
    <div class="info">
      <h1>Корзина</h1>
      <span>(4)</span>
      <ul>
        <li><a href="#">Главная</a></li>
        <li>Полезная информация</li>
      </ul>
    </div>
    <div class="main">
      <div class="orders">
        <div class="orders_list_main">
          <div>
            <input class="input" type="checkbox" />
            <h3 class="checkboxs">Выбрать все</h3>
            <h3>Удалить выбранные</h3>
          </div>
          <hr />
        </div>

        <div class="order">
          <div class="order_info">
            <input type="checkbox" />
            <div class="order_info_image img1">
              <!-- <img src="img/bed1.jpg" alt=""> -->
            </div>
            <div class="order_info_title">
              Наименование изделия
            </div>
          </div>
          <div class="order_amount">
            <div class="order_amount_price">
              <h2>4 600 ₽</h2>
              <h3>старая цена <span>5 800 ₽</span></h3>
            </div>
            <ul>
              <li class="circle">-</li>
              <li>1</li>
              <li class="circle">+</li>
            </ul>
          </div>
          <span class="line"></span>
          <hr />
        </div>
        <div class="order">
          <div class="order_info">
            <input type="checkbox" />
            <div class="order_info_image img2">
              <!-- <img src="img/bed1.jpg" alt=""> -->
            </div>
            <div class="order_info_title">
              Наименование изделия
            </div>
          </div>
          <div class="order_amount">
            <div class="order_amount_price">
              <h2>4 600 ₽</h2>
              <h3>старая цена <span>5 800 ₽</span></h3>
            </div>
            <ul>
              <li class="circle">-</li>
              <li>1</li>
              <li class="circle">+</li>
            </ul>
          </div>
          <span class="line"></span>
          <hr />
        </div>
        <div class="order">
          <div class="order_info">
            <input type="checkbox" />
            <div class="order_info_image img3">
              <!-- <img src="img/bed1.jpg" alt=""> -->
            </div>
            <div class="order_info_title">
              Наименование изделия
            </div>
          </div>
          <div class="order_amount">
            <div class="order_amount_price">
              <h2>4 600 ₽</h2>
              <h3>старая цена <span>5 800 ₽</span></h3>
            </div>
            <ul>
              <li class="circle">-</li>
              <li>1</li>
              <li class="circle">+</li>
            </ul>
          </div>
          <span class="line"></span>
          <hr />
        </div>
        <div class="order">
          <div class="order_info">
            <input type="checkbox" />
            <div class="order_info_image img4">
              <!-- <img src="img/bed1.jpg" alt=""> -->
            </div>
            <div class="order_info_title">
              Наименование изделия
            </div>
          </div>
          <div class="order_amount">
            <div class="order_amount_price">
              <h2>4 600 ₽</h2>
              <h3>старая цена <span>5 800 ₽</span></h3>
            </div>
            <ul>
              <li class="circle">-</li>
              <li>1</li>
              <li class="circle">+</li>
            </ul>
          </div>
          <span class="line"></span>
          <hr />
        </div>
      </div>
      <div class="listOfOrder">
        <div class="listOfOrder_title">Ваша корзина:</div>
        <span class="line"></span>
        <ul>
          <li>Наименование товара <span>4 600 ₽</span></li>
          <li>Балдахин Помпон х2 <span>5 600 ₽</span></li>
          <li>Бортик коса четверного плетения <span>1 800 ₽</span></li>
          <li>Балдахин Принц синий х2 <span>7 000 ₽</span></li>
        </ul>
        <span class="line"></span>
        <div class="score">
          Итого:
          <span>19 000 ₽</span>
        </div>
        <span class="line line3"></span>
        <button class="btn">перейти к оформлению</button>
      </div>
    </div>
  </section>
</template>
<style scoped>
* {
  box-shadow: border-box;
}
body {
  padding-top: 100px;
}
section {
  width: 80%;
  margin-left: 10%;
}
.info h1 {
  font-weight: bold;
  font-size: 42px;
  display: inline-block;
}
.info ul {
  margin-top: -20px;
  padding: 0;
  display: flex;
  flex-direction: row;
}
.info li {
  margin-left: 26px;
  color: rgba(0, 0, 0, 0.4);
}
.info li:nth-child(1) {
  list-style-type: none;
  margin-left: 0;
  color: #60617b;
}
.info a:nth-child(1) {
  color: #5e5f7c;
  text-decoration: none;
  font-size: 13px;
}
.info a {
  color: rbga(0, 0, 0, 0.1);
}
.info span {
  margin-left: 10px;
}
.main {
  display: grid;
  grid-template-columns: 70% 25%;
}
.orders {
  display: flex;
  background: #ffffff;
  box-shadow: 5px 5px 30px rgba(41, 41, 167, 0.12);
  border-radius: 20px;
  padding: 32px 32px 32px 32px;
  flex-direction: column;
  position: relative;
  margin-right: 5%;
}
.orders_list_main {
  height: 40px;
  padding: 0;
}
.orders_list_main div {
  margin: 0;
  padding: 0;
  align-items: center;
  padding-bottom: 10px;
  font-size: 12px;
  text-align: start;
}
.orders_list_main div input {
  display: inline-block;
  margin: 0;
}
.orders_list_main div h3 {
  display: inline-block;
  color: #4e6fb3;
  margin: 0;
  margin-left: 20px;
}
.orders_list_main div .checkboxs {
  color: rgba(0, 0, 0, 0.5);
}
.orders_list_main hr {
  background-color: rgba(0, 0, 0, 0.8);
  color: #ffffff;
}
.orders .order {
  display: grid;
  grid-template-columns: 400px 1fr;
  position: relative;
  padding: 20px 0 20px 0;
}
.orders .order_info {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-direction: row;
  margin-right: 5%;
}
.orders .order_info_title {
  margin-left: 5px;
  letter-spacing: 1px;
  font-size: 18px;
}
.orders .order_info input {
  margin-left: 16px;
  margin: 0;
}
.orders .order_info_image {
  margin-left: 16px;
  width: 120px;
  height: 90px;
  background-image: url("../assets/img/1.png");
  background-repeat: no-repeat;
  background-size: cover;
}
.orders .order_amount {
  display: grid;
  grid-template-columns: 60% 40%;
}
.orders .order_amount_price {
  margin-top: 8%;
  margin-left: 40%;
}
.orders .order_amount_price h2 {
  font-size: 20px;
  font-weight: 500;
}
.orders .order_amount_price h3 {
  line-height: 10px;
  font-size: 12px;
  color: rgba(0, 0, 0, 0.6);
}
.orders .order_amount_price h3 span {
  text-transform: uppercase;
  text-decoration: line-through;
}
.orders .order_amount ul {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  list-style-type: none;
  align-items: center;
  justify-content: center;
}
.orders .order_amount ul li {
  margin-right: 10px;
}
.orders .order_amount ul .circle {
  display: flex;
  cursor: pointer;
  justify-content: center;
  align-items: center;
  width: 40px;
  height: 40px;
  background-color: rgba(77, 56, 203, 0.05);
  border-radius: 100%;
}
.orders .order .line {
  position: absolute;
  bottom: 0;
  height: 1px;
  width: 100%;
  background-color: #b9b8b8;
}
.listOfOrder {
  margin: 0;
  position: relative;
  padding-bottom: 0;
}
.listOfOrder_title {
  font-size: 17px;
  font-weight: 550;
}
ul {
  padding: 0;
  list-style-type: none;
}
ul li {
  margin-top: 20px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  color: rgba(0, 0, 0, 0.7);
}
.score {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0;
  font-size: 16px;
  font-weight: 550;
}
.score span {
  font-weight: 500;
}
.btn {
  width: 100%;
  height: 40px;
  left: 0;
  right: 0;
  bottom: 0;
  align-items: center;
  text-align: center;
  background: #6b8bc9;
  border: 0;
  color: #fff;
  text-transform: uppercase;
  border-radius: 12px;
  cursor: pointer;
}
.btn:focus {
  outline: 0;
}
.line {
  margin-top: 10px;
  display: block;
  width: 100%;
  height: 1px;
  background-color: rgba(0, 0, 0, 0.2);
  margin-bottom: 19px;
}
.line3 {
  margin-top: 15px;
}
</style>
