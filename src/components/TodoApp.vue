<template>
    <div class="todo-app">
        <h1>Todo List App</h1>
        <TodoForm />
        <TodoList />
    </div>
</template>

<script setup>
import TodoForm from './TodoForm.vue';
import TodoList from './TodoList.vue';

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>