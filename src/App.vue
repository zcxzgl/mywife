<template>
  <div id="app">
    <v-header></v-header>
    <v-footer></v-footer>
  </div>
</template>
<script>
import vFooter from "./components/public/footer"
import vHeader from "./components/public/header"

export default {
  name: "App",
  components: {
    vFooter,
    vHeader,
  }
}
</script>
<style lang="scss">

</style>
