<script>
import Jumbotron from "./Jumbotron.vue";
import RealWorldResults from "./RealWorldResults.vue";
export default {
  name: "AppMain",
  components: {
    Jumbotron,
    RealWorldResults
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
    <RealWorldResults></RealWorldResults>
  </main>
</template>

<style lang="scss" scoped>
</style>