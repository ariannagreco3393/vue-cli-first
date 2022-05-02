<template>
  <div id="app">
    <MYtitle/>
    <jumboTron/>
  </div>
</template>

<script>
import MYtitle from './components/title.vue'
import jumboTron from './components/jumbotron.vue'

export default {
  name: 'App',
  components: {
    MYtitle,
    jumboTron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
