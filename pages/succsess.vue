 <template>
  <b-container fluid class="succses">
      <b-row>
      <b-col>
        <h1 class="title">Оплата</h1>
        <b-breadcrumb :items="items"></b-breadcrumb
      ></b-col>
    </b-row>
    <b-row>
      <b-col class="succses__content">
        <h class="succses__content-title"> Поздравляем! </h>
        <p class="succses__content-text">Оплата успешно проведена.</p>
        <b-button variant="outline-primary" class="succses__content-btn">
          На главную
        </b-button>
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
          text: "Корзина и оформление заказа",
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
.succses {
  background: #f7f9fc;
  width: 100%;
  height: 100vh;
 
 
  justify-content: center;
  font-family: "Montserrat";
}
.title{
  margin-top: 48px;
  margin-bottom: 16px;
}
.succses__content {
  margin: 0 25px;
  background: url("../assets/img/succsess.png") no-repeat center center / 100%;
 width: 1271px;
 box-shadow: 5px 5px 30px rgba(41, 41, 167, 0.12);
 
  height: 392px;
  border-radius: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.succses__content-title {
  margin: 43px 0 11px 0;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 24px;
  text-align: center;
  color: #151632;
}
.succses__content-text {
  margin-bottom: 37px;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 17px;
  text-align: center;
  color: #60617b;
}
.succses__content-btn {
  margin-bottom: 37px;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 15px;
  text-transform: uppercase;
  width: 199px;
  height: 39px;
  border: 2px solid rgba(75, 111, 173, 0.3);
  box-sizing: border-box;
  border-radius: 12px;
  color: #6b8bc9;
}
.btn-outline-primary:hover {
  color: #fff;
  background-color: #007bff;
  border-color: #007bff;
}
</style>