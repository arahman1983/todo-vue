<template>
  <div class="w-100 bg-dark">
    <div class="container nav-container">
      <div class="logo">
        <img alt="Vue logo" src="../assets/logo.png" />
        <span>To Do App</span>
      </div>
      <div id="nav">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ToDoHeader",
};
</script>

<style lang="scss" scoped>
.nav-container {
  display: flex;
  justify-content: space-between;
  #nav {
    padding: 30px;

    a {
      font-weight: bold;
      color: #fff;
      margin-inline-start: 16px;
      text-decoration: none;

      &.router-link-exact-active {
        color: #42b983;
      }
    }
  }
  .logo {
    align-self: center;
    img {
      height: 40px;
      margin-inline-end: 16px;
    }
    span {
      color: #fff;
      font-weight: bolder;
      font-size: 20px;
    }
  }
}
</style>
