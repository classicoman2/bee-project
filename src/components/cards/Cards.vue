<template>
  <slot name="capçalera"></slot>
  <h2>{{ descripcio }} - any {{ any+23 }}</h2>
  <slot></slot>
  <ul>
    <li v-for="bee in bees" :key="bee"> {{ bee }}</li>
  </ul>
</template>
<script>
export default {
  name: "Header",
  props: { descripcio: String, any: Number },
  data() {
    return {
      bees: ['maya', 'roberto', 'stuart', 'maria']
    }
  }
}
</script>

<style scoped>

</style>