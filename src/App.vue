<template>
  <div id="app" class="container">
    <AddTodo />
    <FilterTodos />
    <Todos />
  </div>
</template>


<script>
import Todos from './components/Todos';
import AddTodo from './components/AddTodo';
import FilterTodos from "./components/FilterTodos.vue";

export default {
  name: 'App',
  components: {
    Todos,
    AddTodo,
    FilterTodos
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  color: #fff;
  list-style: none;
}

body{
  background: #151515;
}
</style>
