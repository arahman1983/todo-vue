<template>
  <div class="home">
    <todo-element></todo-element>
  </div>
</template>

<script>
import TodoElement from "@/components/TodoElement.vue";
export default {
  name: "Home",
  components: {
    TodoElement,
  },
};
</script>
