<script>
import Navbar from "./Navbar.vue";
export default {
  name: "HomePage",
  components: {
    Navbar,
  },
};
</script>

<template>
  <div class="Home">
    <img class="homeimg" src="../assets/img/Mask group (1).png" alt="" />
  </div>
  <Navbar />
</template>

<style>
.homeimg {
  width: 100%;
  height: 950px !important;
  object-fit: cover;
  position: absolute;
  z-index: -1;
}
</style>
