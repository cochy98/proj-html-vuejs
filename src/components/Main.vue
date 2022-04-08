<template>
  <main>
    <Services />
  </main>
</template>

<script>
import Services from "./main-section/Services.vue";
export default {
  name: "IndexMain",
  components: {
    Services,
  },
};
</script>

<style lang="scss">
/* Importo le variabili scss */
@import "../assets/scss/_variables.scss";
</style>
