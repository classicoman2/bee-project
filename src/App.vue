<script setup>
import BeeDescription from "./components/BeeDescription.vue";
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/images/bee.png" width="125" height="125" />
  </header>
  <main>
    <BeeDescription descripcio="Hola Abelles!" :any="2000">
      <!-- slot sense nom. S'ubica en el template del component en l'etiqueta <slot></slot> </slot>-->
      Això es una prova de Slot
      <template #capçalera>
        Això es la capçalera!
      </template>
    </BeeDescription>
  </main>
</template>

<script>

export default {
  name: "Header",
  props: {},
  data: () => {
    return {
      valorFiltre: "",
    };
  },
  methods: {
    alerta: function () {
      alert("Abelles!")
    },
  },
};
</script>

<style scoped>

</style>
