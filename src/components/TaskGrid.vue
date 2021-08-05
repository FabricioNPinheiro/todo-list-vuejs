<template>
    <div id="tasks">
        <div v-for="task in tasks" :key="task.name"> {{task.name}}</div>
    </div>
</template>

<script>
export default {
  props: {
    tasks: { type: Array, required: true },
  },
};
</script>
