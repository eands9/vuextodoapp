<template>
  <div>
    <AddTodo />
    <FilterTodos />
    <Todos />
  </div>
  <router-view/>
</template>

<script>
import AddTodo from '@/components/AddTodo.vue'
import FilterTodos from '@/components/FilterTodos.vue'
import Todos from '@/components/Todos.vue'

export default {
  name: 'App',
  components: {AddTodo, FilterTodos, Todos}
}
</script>