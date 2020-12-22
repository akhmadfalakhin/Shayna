<template>
  <div class="home">
    <HeaderShayna />
    <Hero />
    <WomenShayna />
    <InstaShayna />
    <PartnerShayna />
    <Footer />
       
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import Hero from '@/components/Hero.vue';
import WomenShayna from '@/components/WomenShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/Partner.vue';
import Footer from '@/components/Footer.vue';


export default {
  name: 'Home',
  components: {
    HeaderShayna,
    Hero,
    WomenShayna,
    InstaShayna,
    PartnerShayna,
    Footer
  }
}
</script>
