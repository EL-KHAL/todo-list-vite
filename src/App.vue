<template>
  <div class="content">
    <TodoList />
  </div>
</template>

<script setup>
import TodoList from "./components/TodoList.vue";
</script>

<style lang="scss">
// global ya khali
:root {
  --background-color: #070707;
  --text-primary: #050504;
  --text-secondary: #030303;
  --todo-bg-color: #fc95d9;
  
}
@import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@1,500&display=swap');
body {
  margin: 0px;
  font-family: 'Kanit', sans-serif;
}
.content {
  background: var(--background-color);
  height: 100vh;
  overflow: hidden;
  position: relative;
}
</style>

