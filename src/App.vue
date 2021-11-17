<template>
  <ToDoHeader></ToDoHeader>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

<script>
import ToDoHeader from "@/components/Header.vue";
export default {
  components: {
    ToDoHeader,
  },
};
</script>
