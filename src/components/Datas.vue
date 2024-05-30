<script setup>
import { computed, reactive } from "vue";
import Product from "./Product.vue";
import Brend from "./Brend.vue";

const products = reactive([
  {
    img: "/images/boy1.png",
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
    sale: false,
    price: 2499,
    info: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
]);

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

const onSaleProducts = computed(() =>
  products.filter((product) => product.sale)
);
const newProducts = computed(() => products.filter((product) => !product.sale));
</script>

<template>
  <div class="container mx-auto">
    <div>
      <div class="mb-10">
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
      </div>
      <div>
        <h1 class="text-3xl my-3">Новинки</h1>
        <div class="grid grid-cols-2 sm:grid-cols-1 md:grid-cols-6 gap-5">
          <div v-for="(product, index) in newProducts" :key="index">
            <Product :product="product" />
          </div>
          <button class="gradient-border border border-gradien py-2">
            Все товары
          </button>
        </div>
      </div>
      <div class="">
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

        <button class="gradient-border border border-gradien py-2 mt-7">
          Все магазины
        </button>
      </div>

      <div>
        <h1 class="text-3xl my-3">Рекомендуемые для вас товары</h1>
        <div class="grid grid-cols-2 sm:grid-cols-1 md:grid-cols-6 gap-5">
          <div v-for="(product, index) in products" :key="index">
            <Product :product="product" />
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
