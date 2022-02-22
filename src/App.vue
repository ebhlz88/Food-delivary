<template>
  <div id="app">
    <mainn></mainn>
  </div>
</template>

<script>
import mainn from './components/main.vue'

export default {
  name: 'App',
  components: {
    mainn
    
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
  margin: 0;
  padding: 0;
}
</style>
