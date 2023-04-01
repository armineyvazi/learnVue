<template>
    <div
      v-for="task in tasks"
      :key="task.text"
      >
      <h3> {{task.text}} </h3>
    </div>
</template>

<script>
export default {
  name: 'Task',
  props: {
    tasks: Array
  }
}
</script>
