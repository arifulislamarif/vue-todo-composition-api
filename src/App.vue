<template>
  <div style="display: flex; justify-content: space-around">
    <div>
      <TodoList title="Todo without Compostion Api "/>
    </div>
    <div>
      <TodoListV3 title="Todo with Compostion Api" />
    </div>
  </div>
</template>
<script>
import TodoList from "./components/TodosList"
import TodoListV3 from "./components/TodoListV3"

export default {
  components: {
    TodoList,
    TodoListV3
  }
}
</script>
