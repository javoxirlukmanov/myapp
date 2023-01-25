<script>
export default {
  name: "NavbarPage",
  data() {
    return {
      showmenu: false,
    };
  },
  methods: {
    showFunction() {
      this.showmenu ? (this.showmenu = false) : (this.showmenu = true);
      console.log(this.showmenu);
    },
  },
};
</script>
<template>
  <div class="container">
    <div class="row">
      <div class="d-flex justify-content-between">
        <div class="col-auto mt-5">
          <div class="navbar-left">
            <div class="d-flex justify-content-around">
              <img class="logo" src="../assets/img/Group 88.png" alt="" />
              <a class="navbar-h1" href="#">Azur Life</a>
              <img src="../assets/img/Vector 44.png" alt="" />
              <a class="navbar-h1" href=""
                ><img src="../assets/img/Exclude.png" alt="" />
              </a>
              <a class="navbar-h1a" href=""
                >Франция, бульвар Леклерк, 46, 06310, Болье-сюр-Мер</a
              >
              <img class="img" src="../assets/img/Vector 44.png" alt="" />

              <a class="navbar-h1" href="">
                <img class="tel" src="../assets/img/Vector.png" alt="" /> +33 4
                93 16 06 31</a
              >
            </div>
          </div>
        </div>

        <div class="col-auto mt-5">
          <a class="navbar-language-changer-en" href="">en</a>
          <a class="navbar-language-changer" href="">fr</a>
          <a class="navbar-language-changer" href="">ru</a>
          <a class="navbar-language-changer" href="">it</a>
          <a class="navbar-language-changer" href="#" @click="showFunction"
            ><img class="menu" src="../assets/img/menu (3).svg" alt=""
          /></a>
          <div
            class="menubar offcanvas offcanvas-end"
            :class="showmenu ? 'show' : ''"
            :Style="{ visibility: showmenu ? 'visible' : 'hidden' }"
          >
            <img
              class="x"
              @click="showFunction"
              src="../assets/img/x.svg"
              alt=""
            />
            <a class="navbar-language-changer-en" href="">en</a>
            <a class="navbar-language-changer" href="">fr</a>
            <a class="navbar-language-changer" href="">ru</a>
            <a class="navbar-language-changer" href="">it</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Lobster&family=Roboto:ital,wght@1,900&display=swap");

.logo {
  width: 25px;
  height: 20px;
  margin: 3px 0px !important;
}
.menu {
  color: rgb(255, 255, 255);
  transform: rotate(90deg);
}
img {
  margin-top: -2px;
}
.img {
  margin-top: -2px;
  margin-left: 10px;
}
.x {
  width: 20px;
  height: 20px;
}

.tel {
  margin-top: -4px;
}

.navbar-h1 {
  font-family: "Playfair Display";
  font-size: 16px;
  color: rgb(255, 255, 255);
  margin: 0 15px;
  text-decoration: none;
}
.navbar-h1a {
  font-family: "Manrope";
  font-size: 16px;
  color: rgb(255, 255, 255);
  margin: 0 5px;
  text-decoration: none;
}
.navbar-language-changer-en {
  font-size: 15px;
  color: rgb(242, 8, 8);
  text-decoration: underline;
  margin: 0 10px;
}

.navbar-language-changer {
  font-size: 15px;
  color: rgb(207, 29, 29);
  margin: 0 10px;
  text-decoration: none;
}
</style>
