<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Workbench></Workbench>
  </div>
</template>

<script>
import Workbench from './components/Workbench'

export default {
  name: 'app',
  components: {
    Workbench
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
