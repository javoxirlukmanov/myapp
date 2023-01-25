<script>
export default {
  name: "ButtonComponent",
  props: {
    name: {
      default: "click me ",
      type: String,
    },
  },
};
</script>

<template>
  <button>{{ name }}</button>
</template>
