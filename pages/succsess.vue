 <template>
  <b-container fluid class="succses">
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
<style scoped>
.succses {
  background: #f7f9fc;
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: "Montserrat";
}
.succses__content {
  background: url("../assets/img/succsess.png") no-repeat center center / 100%;
 width: 1271px;
 
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