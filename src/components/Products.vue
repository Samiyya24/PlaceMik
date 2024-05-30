<script setup>
const props = defineProps({
  products: Object,
});
</script>
<template>
  <div>
    <div class="container mx-auto">
      <div>
        <!-- <div class="mb-10">
          <h1 class="text-3xl my-3">Успей купить</h1>
          <div
            class="relative grid grid-cols-2 sm:grid-cols-1 md:grid-cols-6 gap-5"
          >
            <div v-for="(product, index) in onSaleProducts" :key="index">
              <Product :product="product" />
            </div>
            <button
              class="gradient-border border border-gradien py-2 flex flex-col items-center justify-end"
            >
              Все товары
            </button>
          </div>
        </div> -->
        <!-- <div>
          <h1 class="text-3xl my-3">Новинки</h1>
          <div class="grid grid-cols-2 sm:grid-cols-1 md:grid-cols-6 gap-5">
            <div v-for="(product, index) in newProducts" :key="index">
              <Product :product="product" />
            </div>
            <button class="gradient-border border border-gradien py-2">
              Все товары
            </button>
          </div>
        </div> -->
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
