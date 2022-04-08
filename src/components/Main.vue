<template>
  <main>
    <Services />
    <Work />
    <Articles />
  </main>
</template>

<script>
import Services from "./main-section/Services.vue";
import Work from "./main-section/Work.vue";
import Articles from "./main-section/Articles.vue";
export default {
  name: "IndexMain",
  components: {
    Services,
    Work,
    Articles,
  },
};
</script>

<style lang="scss">
/* Importo le variabili scss */
@import "../assets/scss/_variables.scss";
</style>
