<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <TodoList />
  </div>
</template>

<script>
import TodoList from '@/components/TodoList.vue'

export default {
  name: 'HomeView',
  components: {
    TodoList
  }
}
</script>
