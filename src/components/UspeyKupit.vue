<script setup>
import { reactive } from "vue";
import Product from "./Product.vue";
const products = reactive([
  {
    img: "/images/boy1.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy2.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy1.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy2.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy1.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/hat3.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/hat3.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy1.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy1.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy2.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy1.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/hat3.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/hat3.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/hat3.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/hat3.png",
    salePrice: 1999,
    sale: true,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone1.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    salePrice: 1999,
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
]);
</script>
<template>
  <div class="container mx-auto">
    <div>
      <div class="mb-10">
        <h1 class="text-3xl my-3">Успей купить</h1>
        <div
          class="relative grid grid-cols-2 sm:grid-cols-1 md:grid-cols-6 gap-5"
        >
          <div v-for="(product, index) in products" :key="index">
            <Product :product="product" v-if="product.sale == true" />
          </div>
          <button
            class="gradient-border border border-gradien py-2 flex flex-col items-center justify-end"
          >
            Все товары
          </button>
        </div>
      </div>
      <div>
        <h1 class="text-3xl my-3">Новинки</h1>
        <div class="grid grid-cols-2 sm:grid-cols-1 md:grid-cols-6 gap-5">
          <div v-for="(product, index) in products" :key="index">
            <Product :product="product" v-if="product.sale == false" />
          </div>
          <button class="gradient-border border border-gradien py-2">
            Все товары
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
