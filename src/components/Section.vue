<script>
import Button from "../components/Button.vue";
export default {
  name: "SectionPage",
  components: {
    Button,
  },
};
</script>

<template>
  <div class="Section">
    <img class="Sectionimg" src="../assets/img/Group 94.png" alt="" />
    <div class="white-div-inside">
      <img class="A" src="../assets/img/A.png" alt="" />
      <img class="indirect-text" src="../assets/img/Group.png" alt="" />
      <h2 class="Section-h2">
        “Состоятельные люди приезжают <br />
        на Лазурный берег за спокойствием <br />
        и даже уединением”
      </h2>
      <h3>Forbes</h3>
    </div>
  </div>
  <div class="Section-center">
    <img class="Section-centerimg" src="../assets/img/&.png" alt="" />
    <h1 class="section-center-h1">
      Специалисты <br />
      Azur Life
    </h1>
    <div class="first-woman-div">
      <img
        class="olga-img"
        src="../assets/img/olga-zabegina-KguqaFJS05I-unsplash 1 (1).png"
        alt=""
      />
      <h2 class="section-center-h2-a">Наталья Виноградова</h2>
      <h3 class="section-center-h3-a">
        Специализация: продажа <br />
        и аренда недижимости во Франции. <br />
        Экспертиза: имущественное право, налоги <br />
        и визовые вопросы
      </h3>
    </div>
    <div class="second-woman-div">
      <img
        class="second-woman-img"
        src="../assets/img/unsplash_TSZo17r3m0s.png"
        alt=""
      />
      <h2 class="section-center-h2">Ева Синибальди</h2>
      <h3 class="section-center-h3">
        Специализация: управление недвижимостью <br />
        Экспертиза: оценка недвижимости, <br />
        визовые вопросы
      </h3>
    </div>
    <div class="section-bottom">
      <div class="container">
        <div class="row">
          <div class="col-lg-6">
            <h2 class="section-bottom-h2">Экспертиза агентства</h2>
            <h3 class="section-bottom-h3">
              Azur Life - динамично развивающееся агентство, отстаивающее
              ценности конфиденциальности, лояльности, высокого профессионализма
              и индивидуального подхода с 2017 года. Мы имеем все необходимые
              лицензии, страховые и финансовые гарантии, требуемые французским
              законодательством для того, чтобы провести Вашу сделку по
              недвижимости максимально качественно и комфортно.
            </h3>
            <div class="col-lg-9 d-flex justify-content-between">
              <div class="col-lg-2 d-flex justify-content-between">
                <p class="numbers-7">7</p>
                <img
                  class="line-through"
                  src="../assets/img/Vector 3.png"
                  alt=""
                />
              </div>
              <div class="col-lg-3 d-flex justify-content-between">
                <p class="numbers-27">27</p>
                <img
                  class="line-through"
                  src="../assets/img/Vector 3.png"
                  alt=""
                />
              </div>
              <div class="col-lg-3 d-flex justify-content-between">
                <p class="numbers-last">240</p>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <img
              class="section-bottom-img"
              src="../assets/img/unsplash_wS73LE0GnKs (1).png"
              alt=""
            />
          </div>
        </div>
        <Button class="bottom-button" name="Купить или продать с нами" />
      </div>
      <div class="col-lg-12 d-flex justify-content-around">
        <h5 class="bottom-h5">Вернуться на главную страницу</h5>
        <h5 class="bottom-h5">Все объекты</h5>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");

.Section {
  position: relative;
}
.Sectionimg {
  width: 100%;
  height: 760px;
  object-fit: cover;
  position: absolute;
  z-index: -2;
  background-color: rgba(0, 0, 0, 0.922) !important;
}
.olga-img {
  height: 720px !important;
  position: relative;
}
.first-woman-div {
  width: auto;
  height: auto;
  position: absolute;
  top: 300px;
  left: 45%;
}
.second-woman-div {
  height: 584.943603515625px;
  width: 390px;

  position: relative;
  top: 120px;
  left: 23%;
}

.section-center-h1 {
  font-family: "Playfair Display";
  margin-top: 0px;
  font-size: 85px;
  font-weight: 400;
  text-align: left;
  color: #fff;
  margin-left: 7.5%;
  padding-top: 250px;
}
.section-center-h2 {
  font-family: "Manrope";
  position: absolute;
  top: 60% !important;
  left: 5%;
  font-size: 20px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: right;
  color: #fff;
}
.section-center-h2::after {
  content: "Брокер";
  font-family: "Manrope";
  position: absolute;
  top: 20px;
  left: 67%;
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: right;
}
.section-center-h3 {
  position: absolute;
  top: 70%;
  left: -35%;
  font-family: "Manrope";
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  color: #fff;
  text-align: right;
}
.section-center-h2-a {
  font-family: "Manrope";
  position: absolute;
  top: 80% !important;
  left: 50%;
  font-size: 20px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: right;
  color: #fff;
}
.section-center-h2-a::after {
  content: "Основатель агентства";
  font-family: "Manrope";
  position: absolute;
  top: 20px;
  left: 0%;
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: right;
}
.section-center-h3-a {
  position: absolute;
  top: 90%;
  left: 50%;
  width: 300px;
  font-family: "Manrope";
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  color: #fff;
  text-align: left;
}

.Section-centerimg {
  height: auto;
  width: 70%;
  border-radius: 0px;

  object-fit: cover;
  position: absolute;
  top: 300px !important;
  left: 15%;
}
.A {
  z-index: 10;
  position: absolute;
  top: 0px;
  left: 460px !important;
}
h3 {
  font-family: "Manrope";
  font-size: 25px;
  font-weight: 600;
  line-height: 24px;
  letter-spacing: 0em;
  padding-top: 20px;
  text-align: center;
}
.white-div-inside {
  position: relative;
  height: 758px;
  width: 85%;
  left: 7.5%;
  top: 100px;
  border-radius: 0px;
  z-index: 1;
  background-color: #fffbf2;
}
.Section-h2 {
  padding-top: 300px;
  width: 100%;
  font-family: "Playfair Display";
  font-size: 62px;
  font-weight: 400;
  line-height: 56px;
  letter-spacing: -0.02em;
  text-align: center;
}
.indirect-text {
  position: absolute;
  top: 35%;
  left: 81%;
}
.Section-center {
  height: 1400px;
  width: 100%;
  position: relative;
  border-radius: -20px !important;
  background-color: #000;
}
.section-bottom {
  background-color: rgba(0, 0, 0, 0.912);
  position: relative;
  height: 1000px;
  width: 100%;
  margin-top: 250px;
  z-index: 1;
}
.section-bottom-h2 {
  font-family: "Playfair Display";
  font-size: 85px;
  font-weight: 400;
  line-height: 76px;
  letter-spacing: -0.02em;
  text-align: left;
  color: #fff;
  padding-top: 180px;
}
.section-bottom-h3 {
  font-family: "Manrope";
  width: 400px;
  font-size: 15px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: left;
  color: #fff;
}
.section-bottom-img {
  height: 750px;
  width: 586px;
  margin-top: 80px;
  border-radius: 0px;
}
.numbers-7 {
  font-family: "Playfair Display";
  position: relative;
  font-size: 85px;
  font-weight: 400;
  line-height: 76px;
  letter-spacing: -0.02em;
  text-align: left;
  color: #fff;
}
.numbers-7::after {
  content: "лет на рынке";
  position: absolute;
  left: 0px;
  top: 90px;
  font-family: "Manrope";
  font-size: 12px;
  font-weight: lighter;
  line-height: 14px;
  letter-spacing: 0em;
  text-align: center;
}
.numbers-27 {
  font-family: "Playfair Display";
  position: relative;
  font-size: 85px;
  font-weight: 400;
  line-height: 76px;
  letter-spacing: -0.02em;
  text-align: left;
  color: #fff;
}
.numbers-27::after {
  content: "постоянных клиентов";
  position: absolute;
  left: 0px;
  top: 90px;
  font-family: "Manrope";
  font-size: 12px;
  font-weight: lighter;
  line-height: 14px;
  letter-spacing: 0em;
  text-align: center;
}
.numbers-last {
  font-family: "Playfair Display";
  position: relative;
  font-size: 85px;
  font-weight: 400;
  line-height: 76px;
  letter-spacing: -0.02em;
  text-align: left;
  color: #fff;
}
.numbers-last::after {
  content: "сделок с недвижимостью";
  position: absolute;
  left: 0px;
  top: 90px;
  font-family: "Manrope";
  font-size: 12px;
  font-weight: lighter;
  line-height: 14px;
  letter-spacing: 0em;
  text-align: center;
}
.line-through {
  height: 2px;
  width: 73px;
  margin-top: 100px;
  border-radius: 0px;
}
.bottom-button {
  height: 57px;
  width: 236px;
  position: absolute;
  top: 76%;
  left: 7%;
  border-radius: 7px;
  outline: none;
  color: #fff;
  background-color: rgba(0, 0, 0, 0.442);
}
.bottom-h5 {
  font-family: "Manrope";
  font-size: 20px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: left;
  color: #fff;
  margin-top: 100px;
  transition: 500ms;
}
.bottom-h5:hover {
  text-decoration: underline;
}
</style>
