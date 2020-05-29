<template>
  <div class="product">
   <HeaderSyna />
    <Detail />
    <RelateProduct />
   <FooterSyna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSyna from '@/components/HeaderSyna.vue';
import Detail from '@/components/product/Detail.vue';
import RelateProduct from '@/components/product/RelateProduct.vue';
import FooterSyna from '@/components/FooterSyna.vue';

export default {
  name: 'product',
  components: {
    HeaderSyna,
    Detail,
    RelateProduct,
    FooterSyna,
  }
  
}
</script>
