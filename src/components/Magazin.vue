<script setup>
import Brend from "./Brend.vue";
const marple = [
  { img: ["/images/t-short1.png", "/images/boy1.png", "/images/t-short6.png"] },
];
</script>
<template>
  <div class="container mt-10">
    <h1 class="text-3xl">Магазины для вас</h1>
    <div v-for="marple,index in marple"></div>
  </div>
</template>

<style lang="scss" scoped></style>
