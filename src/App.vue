<template>
  <div id="app">
    <Cinema/>
  </div>
</template>

<script>
import Cinema from './components/Cinema.vue'

export default {
  name: 'App',
  components: {
    Cinema
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
