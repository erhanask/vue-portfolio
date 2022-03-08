<template>
  <div id="app">
    <Navbar />
    <Header />
  </div>
</template>


<script>
import Header from "./components/Header";
import Navbar from "./components/Navbar";

export default {
  name: "App",
  components: {
    Navbar,
    Header,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
