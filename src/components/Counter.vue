<script setup>
import { ref } from "vue";
const count = ref(0);
</script>

<template>
  <h1>this is counter</h1>
  {{ count }}
  <button @click="count++">+</button>
</template>
