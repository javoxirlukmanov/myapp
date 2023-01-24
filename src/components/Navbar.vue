<script>
export default {
  name: "Navbarpage",
  data(){
    return{
      count:0
    }
  }
 }
</script>

<template>
<ul class="navbar-ul">
  <li class="navbar-li"><a class="navbar-a" href=""><img src="../assets/img/Group 88.png" alt=""></a></li>
  <li class="navbar-li"><a class="navbar-a" href="">Azur Life</a></li>
</ul>
</template>

<style>

.navbar-ul{
  display: flex;
}
.navbar-li{
  padding: 20px 10px;
}
.navbar-a{
  font-family: Manrope;
font-size: 15px;
font-weight: 400;
line-height: 24px;
letter-spacing: 0em;
text-align: left;
color: #FFFFFF;
text-decoration: none;

}
</style>