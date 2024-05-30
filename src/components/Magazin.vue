<script setup>
import Brend from "./Brend.vue";
const marples = [
  {
    img: ["/images/t-shirt1.png", "/images/boy1.png", "/images/t-shirt6.png"],
    name: "Marple ",
    logo: "/images/logo6.png",
  },
  {
    img: ["/images/t-shirt1.png", "/images/boy1.png", "/images/t-shirt6.png"],
    name: "Huawei",
    logo: "/images/logo3.png",
  },
  {
    img: ["/images/t-shirt1.png", "/images/boy1.png", "/images/t-shirt6.png"],
    name: "Berlingo",
    logo: "/images/logo7.png",
  },
  {
    img: ["/images/t-shirt1.png", "/images/boy1.png", "/images/t-shirt6.png"],
    name: "U-kwai",
    logo: "/images/logo2.png",
  },
  {
    img: ["/images/t-shirt1.png", "/images/boy1.png", "/images/t-shirt6.png"],
    name: "Lassie",
    logo: "/images/logo4.png",
  },
  {
    img: ["/images/t-shirt1.png", "/images/boy1.png", "/images/t-shirt6.png"],
    name: "Densel",
    logo: "/images/logo1.png",
  },
];
</script>
<template>
  <div class="container mt-10">
    <h1 class="text-3xl mb-7">Магазины для вас</h1>
    <div class="flex items-center gap-8">
      <div class="grid grid-cols-3 gap-8">
        <div v-for="(marple, index) in marples" :key="index">
          <Brend :marple="marple" />
        </div>
      </div>
      <div class="flex flex-col gap-5 w-[24%]">
        <img src="/images/image2.png" alt="" />
        <img src="/images/image1.png" alt="" />
      </div>
    </div>
    <button
      class="group-hover:block hidden py-2 mt-3 bg-gradient-to-r from-purple-500 to-pink-500 text-white w-full"
    >
      Все магазины
    </button>
  </div>
</template>

<style lang="scss" scoped></style>
