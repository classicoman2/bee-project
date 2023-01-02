<script setup>
import Cards from '@/components/cards/Cards.vue';
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
</script>


<template>
  <Header></Header>
  <main>
    <Cards descripcio="Hola Abelles!" :any="2000">
      <!-- slot sense nom. S'ubica en el template del component en l'etiqueta <slot></slot> </slot>--> Això es una prova
      de Slot <template #capçalera> Això es la capçalera! </template>
    </Cards>
  </main>
  <Footer></Footer>
</template>


<style scoped>

</style>