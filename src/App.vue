<template>
  <div id="app">
    <UnderConstruction />
  </div>
</template>

<script>
import UnderConstruction from './components/UnderConstruction.vue'

export default {
  name: 'App',
  components: {
    UnderConstruction
  }
}
</script>

<style>
#app {
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  font-size: 24pt;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  -webkit-text-stroke: 2px black;
  text-decoration: black;
  color: #ffffff;
  margin: auto !important;
  width: 98%;
  height: 95vh;
  background-color: rgb(120, 120, 130);
  border: ridge 10px rgb(75, 80, 87);
}
</style>
