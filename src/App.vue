<script setup>
import Home from "@/components/Home.vue";
</script>

<template>
  <Home></Home>
</template>

<script>

export default {
  name: "Header",
  props: {},
  data: () => {
    return {
      cardsInfo: [{ title: "Innovative Data Driven Solutions", contents: "The World Bee Project is developing data driven innovative solutions such as the World Hive Network© to address pollinator health challenges in cities as well as in smallholder farms and agriculture and food supply chains." },
      { title: "We need Bees", contents: "Over 75% of the nutritious food we eat depends on pollination. Pollination sustains global food security, crop production, farmer livelihoods, wild plant diversity, ecosystem balance, healthy soils and clean air." },
      { title: "Connecting Hives, Connecting Lives", contents: "The World Bee Project supports, connects, and amplifies new technologies and scientific study to improve the health and wellbeing of bees and other pollinators. It uses Artificial Intelligence (AI), data analytics and the Internet of Things (IoT) to power the World Hive Network© to generate solutions to wider issues of biodiversity, climate change, food security and human wellbeing." },
      { title: "The Bees Need Us", contents: "Intensive farming, harmful pesticides, overpopulation, urban sprawl, loss of floral habitats, deforestation and climate change are all placing devastating pressures on pollinators. We address the need for data-based  understanding and nature positive solutions." }]
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
main {
  display: grid;
  grid-template-columns: 1fr;
}
</style>
