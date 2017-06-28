<template>
  <div class="main-canvas">
    {{msg}}
    <context-menu></context-menu>
  </div>
</template>

<script>
import ContextMenu from './ContextMenu'

export default {
  name: 'workbench',
  components: {
    ContextMenu
  },
  data () {
    return {
      msg: 'Welcome to my workbench!'
    }
  }
}
</script>

<style scoped>
  .main-canvas {
    width: 50%;
    min-height: 50vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    border-radius: 1em;
    background: #f00;
    overflow: hidden;
    box-shadow: 0 0 5px rgba(25,25,25,.25);
  }
</style>
