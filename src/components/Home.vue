<script setup>
import Cards from '@/components/cards/Cards.vue';
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
</script>


<template>
  <Header></Header>
  <main>
    <Cards descripcio="Hola Abelles!" :any="2000">
    </Cards>
  </main>
  <Footer></Footer>
</template>


<style scoped>

</style>