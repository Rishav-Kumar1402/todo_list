<template>
<div id="app">
<todo-app>
  
</todo-app>
</div>
</template>

<script>
import TodoApp from './components/TodoApp.vue'

export default {
  name: 'App',
  components: {
    TodoApp
  }
}
</script>

<style>
#app{
  background-color: rgb(182, 238, 234);
  min-height: 100vh;
}
</style>
