<template>
  <div id="app">
    <HelloMike />
  </div>
</template>
<script>
import HelloMike from './components/HelloMike.vue'


export default {
  name: 'App',
  components: {
    HelloMike
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
