<template>
  <header class="header">
    <h1>Todolist</h1>
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  background: #333;
  color: #fff;
  text-align: center;
}

.header a {
  color: #fff;
  padding-right: 5p;
  text-decoration: none;
}
</style>



