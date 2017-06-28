<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div id="main-panel">
      <workbench></workbench>
    </div>
  </div>
</template>

<script>
import Workbench from './components/Workbench'
import ContextMenu from './components/ContextMenu'

export default {
  name: 'app',
  components: {
    Workbench,
    ContextMenu
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
#main-panel {
  overflow: hidden;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: $font-family;
}
</style>
