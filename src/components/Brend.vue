<script setup>
const props = defineProps({
  product: Object,
});
</script>
<template>
  <div>
    <img :src="product.img" alt="" />
  </div>
</template>

<style lang="scss" scoped></style>
