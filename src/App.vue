<template lang="pug">
#app
  router-view
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator"

@Component
export class App extends Vue {}
export default App
</script>

<style lang="sass">
#app 
  font-family: Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px
</style>
