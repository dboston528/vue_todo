<template>
  <div id="app">
    <div id="nav">
      <Header/>
    </div>
    <router-view/>
  </div>
</template>

<script>
import Header from "./components/layout/Header";
export default {
  name: "app",
  components: {
    Header
  }
};
</script>


<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.btn {
  display: inline-block;
  border: none;
  background: #555;
  color: #fff;
  padding: 7px 20px;
  cursor: pointer;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.3;
}
</style>
