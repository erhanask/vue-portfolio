<template>
  <div id="app">
    <Navbar />
    <Header />
    <Cards />
  </div>
</template>


<script>
import Header from "./components/Header";
import Navbar from "./components/Navbar";
import Cards from "./components/Cards";

export default {
  name: "App",
  components: {
    Navbar,
    Header,
    Cards,
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
  background-color: black;
}
</style>
