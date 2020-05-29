<template>
  <div class="home">
   <HeaderSyna />
   <SectionSyna />
   <SectionCarousel />
   <InstaSyna />
   <PartnerSyna />
   <FooterSyna />
   
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSyna from '@/components/HeaderSyna.vue';
import SectionSyna from '@/components/SectionSyna.vue';
import SectionCarousel from '@/components/SectionCarousel.vue';
import InstaSyna from '@/components/InstaSyna.vue';
import PartnerSyna from '@/components/PartnerSyna.vue';
import FooterSyna from '@/components/FooterSyna.vue';

export default {
  name: 'Home',
  components: {
    HeaderSyna,
    SectionSyna,
    SectionCarousel,
    InstaSyna,
    PartnerSyna,
    FooterSyna,
  }
}
</script>
