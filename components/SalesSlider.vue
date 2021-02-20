<template>
  <section>
    <div class="header">
      <div class="title">
        <h1>Акции и скидки</h1>
        <span>(17)</span>
      </div>
      <div class="show-all">
        <a href="#">смотреть все</a>
      </div>
    </div>
    <div class="cards-container">
      <div class="left">
        <span>
          <i class="fas fa-chevron-left"></i>
        </span>
      </div>
      <div class="cards">
        <div class="card">
          <div class="card_image">
            <div class="action">Акция</div>
          </div>
          <div class="card_info">
            <div class="price">
              <div class="newprice">4600 ₽</div>
              <div class="oldprice">5 800 ₽</div>
            </div>
            <div class="title">Наименование изделия</div>
            <div class="voises">
              <ul>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <span class="score">4,3</span>
              </ul>
              <div class="void">
                <i class="far fa-comment-dots"></i>
                <span>28</span>
                отзывов
              </div>
            </div>
            <button class="btn">В корзину</button>
          </div>
        </div>
        <div class="card">
          <div class="card_image">
            <img src="/img/bed2.jpg" alt="" />
            <div class="action">Акция</div>
          </div>
          <div class="card_info">
            <div class="price">
              <div class="newprice">4600 ₽</div>
              <div class="oldprice">5 800 ₽</div>
            </div>
            <div class="title">Наименование изделия</div>
            <div class="voises">
              <ul>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <span class="score">4,3</span>
              </ul>
              <div class="void">
                <i class="far fa-comment-dots"></i>
                <span>28</span>
                отзывов
              </div>
            </div>
            <button class="btn">В корзину</button>
          </div>
        </div>
        <div class="card">
          <div class="card_image">
            <img src="/img/bed2.jpg" alt="" />
            <div class="action">Акция</div>
          </div>
          <div class="card_info">
            <div class="price">
              <div class="newprice">4600 ₽</div>
              <div class="oldprice">5 800 ₽</div>
            </div>
            <div class="title">Наименование изделия</div>
            <div class="voises">
              <ul>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <span class="score">4,3</span>
              </ul>
              <div class="void">
                <i class="far fa-comment-dots"></i>
                <span>28</span>
                отзывов
              </div>
            </div>
            <button class="btn">В корзину</button>
          </div>
        </div>
        <div class="card">
          <div class="card_image">
            <img src="/img/bed2.jpg" alt="" />
            <div class="action">Акция</div>
          </div>
          <div class="card_info">
            <div class="price">
              <div class="newprice">4600 ₽</div>
              <div class="oldprice">5 800 ₽</div>
            </div>
            <div class="title">Наименование изделия</div>
            <div class="voises">
              <ul>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <span class="score">4,3</span>
              </ul>
              <div class="void">
                <i class="far fa-comment-dots"></i>
                <span>28</span>
                отзывов
              </div>
            </div>
            <button class="btn">В корзину</button>
          </div>
        </div>
        <div class="card">
          <div class="card_image">
            <img src="/img/bed2.jpg" alt="" />
            <div class="action">Акция</div>
          </div>
          <div class="card_info">
            <div class="price">
              <div class="newprice">4600 ₽</div>
              <div class="oldprice">5 800 ₽</div>
            </div>
            <div class="title">Наименование изделия</div>
            <div class="voises">
              <ul>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <li><i class="far fa-star"></i></li>
                <span class="score">4,3</span>
              </ul>
              <div class="void">
                <i class="far fa-comment-dots"></i>
                <span>28</span>
                отзывов
              </div>
            </div>
            <button class="btn">В корзину</button>
          </div>
        </div>
      </div>
      <div class="right">
        <span>
          <i class="fas fa-chevron-right"></i>
        </span>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
section {
  height: 500px;
  border: 1px solid green;
  .header {
    .title {
      h1 {
      }
      span {
      }
    }
    .show-all {
      a {
      }
    }
  }
  .cards-container {
  }
}
.container_cards {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.container_cards .card {
  margin-left: 24px;
  max-width: 305px;
  height: 437px;
  background-color: #ffffff;
  border-radius: 10px;
  border: none;
  display: flex;
  flex-direction: column;
  overflow: hidden;
  padding: 15px 15px 0 15px;
  box-shadow: 5px 5px 30px 0px rgba(41, 41, 167, 0.12);
}
.container_cards .card_image {
  /* img/bed2.jpg */
  background-image: url("~assets/img/Rectangle 61.png");
  overflow: hidden;
  top: 0;
  left: 0;
  position: relative;
}
.container_cards .card_image img {
  height: 265px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  position: relative;
}
.container_cards .card_image .action {
  display: flex;
  position: absolute;
  left: 15px;
  bottom: 16px;
  width: 71px;
  height: 28px;
  background: #f160ae;
  font-family: "Montserrat", sans-serif;
  justify-content: center;
  align-items: center;
  text-align: center;
  border-radius: 20px;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 600;
  font-size: 10px;
}
.container_cards .card_info {
  padding-top: 16px;
}
.container_cards .card_info .price {
  display: flex;
  flex-direction: row;
}
.container_cards .card_info .price .newprice {
  color: #de2996;
  font-size: 16px;
  font-family: "Montserrat";
  font-weight: bold;
}
.container_cards .card_info .price .oldprice {
  display: flex;
  align-items: center;
  margin-left: 14px;
  font-size: 12px;
  color: #8889b3;
  text-decoration: line-through;
}
.container_cards .card_info .title {
  margin-top: 11px;
  font-style: normal;
  font-weight: 550px;
  font-size: 16px;
  letter-spacing: 1px;
}
.container_cards .card_info .voises {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.container_cards .card_info .voises ul {
  padding: 0;
  font-size: 12px;
  list-style-type: none;
  display: flex;
  flex-direction: row;
}
.container_cards .card_info .voises ul i {
  color: #f4c15c;
}
.container_cards .card_info .voises ul .score {
  margin-left: 10px;
  color: rgba(0, 0, 0, 0.5);
}
.container_cards .card_info .void {
  color: rgba(0, 0, 0, 0.5);
  font-weight: normal;
  font-size: 12px;
}
.container_cards .card_info .btn {
  margin-top: 150px;
  display: block;
  margin: 0 auto;
  width: 200px;
  height: 40px;
  font-weight: 500;
  font-size: 12px;
  background-color: #fff;
  border-radius: 15px;
  border: 1px solid #6b8bc9;
  text-transform: uppercase;
  color: #6b8bc9;
  cursor: pointer;
}
.left,
.right {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.left span,
.right span {
  width: 40px;
  height: 40px;
  background-color: rgba(75, 111, 173, 0.2);
  border-radius: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  transform: translateY(-30px);
  cursor: pointer;
}
.left span:hover i,
.right span:hover i {
  color: #fff;
}
.left i,
.right i {
  font-size: 20px;
  color: rgba(75, 111, 173, 0.6);
}
.right span {
  margin-left: 24px;
}
.topic {
  margin-left: 90px;
}
.topic h1 {
  display: inline-block;
}
.topic span {
  margin-left: 10px;
  color: rgba(0, 0, 0, 0.4);
}
</style>