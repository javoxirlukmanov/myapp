<script>
import Navbar from "./Navbar.vue"
export default {
  name: "HomePage",
  components:{
  Navbar
 }
 }

</script>

<template>
<div class="Home">
  <img class="homeimg" src="../assets/img/photo_2023-01-23_16-26-24.jpg" alt="">
</div>
<Navbar />
</template>

<style>

.homeimg{
  width: 100%;
  height: 100vh;
  object-fit: cover;
  position: absolute;
  z-index: -1;
}
</style>