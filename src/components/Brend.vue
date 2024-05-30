<script setup>
const props = defineProps({
  marple: Object,
  required: true,
});
</script>
<template>
  <div class="flex">
    <div class="bg-white py-8 px-5 shadow-3xl">
      <div class="flex items-center mb-5 gap-3">
        <img :src="marple.logo" alt="" />
        <h1 class="text-2xl">{{ marple.name }}</h1>
      </div>
      <div class="flex gap-3">
        <img
          class="w-[90px]"
          v-for="(img, index) in marple.img"
          :src="img"
          :key="index"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
