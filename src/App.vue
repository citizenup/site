<template>
  <div id="app">
    <citizen-up msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import CitizenUp from "./components/CitizenUp.vue";

export default {
  name: "app",
  components: {
    CitizenUp
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  margin-left: 30%;
  margin-right: 30%;
}
</style>
