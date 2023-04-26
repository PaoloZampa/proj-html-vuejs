<script>
import Jumbotron from "./Jumbotron.vue";
import RealWorldResults from "./RealWorldResults.vue";
import WorldClassGym from "./WorldClassGym.vue";
import FormSection from "./FormSection.vue";

export default {
  name: "AppMain",
  components: {
    Jumbotron,
    RealWorldResults,
    WorldClassGym,
    FormSection,
},
  data() {
    return {
    }
  },
}
</script>

<template>
  <main>
    <Jumbotron></Jumbotron>
    <WorldClassGym></WorldClassGym>
    <FormSection></FormSection>
    <RealWorldResults></RealWorldResults>
  </main>
</template>

<style lang="scss" scoped>
</style>