<template>
  <div id="app">
    <app-header></app-header>
    <Home />
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    "app-header": Header,
    "app-footer": Footer,
    Home,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: flex;
  flex-direction: column;
  text-align: center;
  min-height: 100vh;
}
ul {
  list-style-type: none;
  padding-left: 0;
}
</style>
