<template>
  <div class="Shoping-Cart">
   <HeaderSyna />
   <ShopingCart />
   <FooterSyna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSyna from '@/components/HeaderSyna.vue';
import ShopingCart from '@/components/product/ShopingCart.vue';
import FooterSyna from '@/components/FooterSyna.vue';

export default {
  name: 'product',
  components: {
    HeaderSyna,
    ShopingCart,
    FooterSyna,
  }
  
}
</script>
