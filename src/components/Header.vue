<script>
import Navbar from "./navbar.vue";
import Button from "./Button.vue";

export default {
  name: "app",

  data() {
    return {
      count: 0,
    };
  },

  components: {
    Navbar,
    Button,
  },
};
</script>
<template>
  <div class="home"></div>
  <div class="container">
    <div class="row">
      <div class="text">
        <p class="header-p-12">Главная страницы > О нас</p>

        <h1>
          Сделки <br />
          на русском языке <br />
          Вашей недвижимостью <br />
          во Франции <br />
          2017 года
        </h1>
        <div class="text-button">
          <p>
            Открываем новые горизонты Франции для Вас. Мы подберем недвижимость
            исходя из озвученных запросов, обеспечим управление вашими
            апартаментами или окажем услугу консьерж-сервиса, а вам остается
            только одно: наслаждаться жизнью.
          </p>
        </div>
        <div class="mt-5">
          <Button class="header-button" name="Напишите нам" />
        </div>
      </div>
    </div>
  </div>
  <Section />
</template>
<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");

.home {
  display: flex;
  position: relative;
  width: 100%;
}
.home-img {
  width: 100%;

  object-fit: cover;
  position: absolute;
  z-index: -1;
}
.text {
  font-family: "Playfair" Display;
  width: 65%;
  padding-top: 0px;
}
.header-p-12 {
  font-family: "Manrope";
  font-style: normal;
  font-size: 12px;
  line-height: 160%;
  color: rgba(255, 255, 255, 0.6);
  margin-top: 30px !important;
}
.text h1 {
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: 400;
  font-size: 71px;
  line-height: 90%;
  color: #fff;
}
.text-button {
  width: 53%;
  color: #fff;
}
.p15 {
  font-size: 15px;
  color: #fff;
  text-decoration: underline;
}
.header-button {
  background: #fff9ec;
  border-radius: 7px;
  border: none;
  font-size: 15px;
  color: #be7e00;
  padding: 15px;
  margin-bottom: 0rem;
}
p {
  font-family: Manrope;
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: left;
  margin-top: 40px;
}
h1 {
  font-family: Playfair Display;
  font-size: 85px;
  font-weight: 400;
  line-height: 76px;
  letter-spacing: -0.02em;
  text-align: left;
  margin-top: 60px;
}
</style>
