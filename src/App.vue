<template>
  <div id="app">
    <top-menu></top-menu>
  </div>
</template>

<script>
import TopMenu from './components/navbar/top_menu.vue'

export default {
  name: 'App',
  components: {
    TopMenu
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
