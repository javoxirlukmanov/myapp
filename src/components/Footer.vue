<script>
import Button from "../components/Button.vue";
export default {
  name: "FooterPage",
  components: {
    Button,
  },
};
</script>

<template>
  <div class="Footer">
    <img class="Footerimg" src="../assets/img/Mask group (2).png" alt="" />
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-4 height d-flex flex-column justify-content-around">
          <div class="col-lg-12">
            <h2 class="Footer-h2">Перезвоните мне</h2>
            <input class="inputs" type="text" placeholder="Имя" />
            <input class="inputs" type="text" placeholder="Телефон" />
            <input class="inputs" type="text" placeholder="Email" />
            <h3 class="Footer-h3">Отправить запрос</h3>
          </div>
          <div class="col-lg-12 d-flex justify-content-between">
            <div class="col-lg-4 d-flex justify-content-between">
              <img class="icon-1" src="../assets/img/Vector (1).png" alt="" />
              <h3 class="Footer-h3">+33 4 93 16 06 31</h3>
            </div>
            <div class="col-lg-2 d-flex justify-content-between">
              <img class="icon-2" src="../assets/img/Group (1).png" alt="" />
              <img class="icon-2" src="../assets/img/Subtract (1).png" alt="" />
            </div>
          </div>
          <div class="col-lg-12 d-flex justify-content-between">
            <div class="col-lg-5 d-flex justify-content-between">
              <img class="icon-1" src="../assets/img/Subtract.png" alt="" />
              <h3 class="Footer-h3">contact@azur-life.com</h3>
            </div>
          </div>
          <div class="col-lg-12 d-flex justify-content-between">
            <div class="col-lg-11 d-flex justify-content-between">
              <img class="icon-1" src="../assets/img/Exclude (1).png" alt="" />
              <h3 class="Footer-h3">
                Франция, бульвар Леклерк, 46, 06310, Болье-сюр-Мер
              </h3>
            </div>
          </div>
        </div>
        <div class="col-lg-5 d-flex justify-content-between">
          <div class="row">
            <div class="col-lg-6"><h3 class="Footer-h3">Навигация</h3></div>
            <div class="col-lg-6"><h3 class="Footer-h3">Регионы</h3></div>
            <div class="col-lg-6">
              <h3 class="Footer-h3">Апартаменты в Больё-сюр-Мер</h3>
            </div>
            <div class="col-lg-6"><h3 class="Footer-h3">О нас</h3></div>
            <div class="col-lg-6"><h3 class="Footer-h3">Все объекты</h3></div>
            <div class="col-lg-6">
              <h3 class="Footer-h3">Вилла в Больё-сюр-Мер</h3>
            </div>
            <div class="col-lg-6"><h3 class="Footer-h3">Продажа</h3></div>
            <div class="col-lg-6"><h3 class="Footer-h3">Вилла в Эзе</h3></div>
            <div class="col-lg-6"><h3 class="Footer-h3">Аренда</h3></div>
            <div class="col-lg-6">
              <h3 class="Footer-h3">Вилла в Сен-Жан-Кап-Ферра</h3>
            </div>
            <div class="col-lg-6">
              <h3 class="Footer-h3">Купить, продать, арендовать с нами</h3>
            </div>
            <div class="col-lg-6">
              <h3 class="Footer-h3">Апартаменты в Эзе</h3>
            </div>
            <div class="col-lg-6"><h3 class="Footer-h3">Презентация</h3></div>
            <div class="col-lg-6">
              <h3 class="Footer-h3">Апартаменты в Сен-Жан-Кап-Ферра</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");
.Footer {
  margin-top: 847px;
  z-index: -2;
}
.icon-1 {
  margin-top: 40px !important;
  width: 20px;
  height: 20px;
}
.icon-2 {
  margin-top: 40px;
  width: 28px;
  height: 28px;
}
.Footerimg {
  width: 100%;
  height: 760px;
  object-fit: cover;
  position: absolute;
  z-index: -1;
  background-color: rgba(0, 0, 0, 0.922) !important;
}

.height {
  height: 760px;
}
.Footer-h2 {
  font-family: "Manrope";
  font-size: 15px;
  font-weight: 500;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: left;
  color: #fff;
}
.inputs {
  height: 30px;
  width: 401.5px;
  left: 125px;
  top: 200px;
  margin-top: 20px;
  border-radius: 0px;
  border: 0px;
  border-bottom: 1px solid #fff;
  background-color: rgba(255, 255, 255, 0);
}
.Footer-h3 {
  font-family: "Manrope";
  font-size: 15px;
  font-weight: 500;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: right;
  color: #fff;
  margin-top: 20px;
}
</style>
