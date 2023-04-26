<script>
import Jumbotron from "./Jumbotron.vue";
import RealWorldResults from "./RealWorldResults.vue";
import WorldClassGym from "./WorldClassGym.vue";
import FormSection from "./FormSection.vue";
import OptionsSection from "./OptionsSection.vue"

export default {
  name: "AppMain",
  components: {
    Jumbotron,
    RealWorldResults,
    WorldClassGym,
    FormSection,
    OptionsSection,
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
    <OptionsSection></OptionsSection>
    <RealWorldResults></RealWorldResults>
  </main>
</template>

<style lang="scss" scoped>
</style>