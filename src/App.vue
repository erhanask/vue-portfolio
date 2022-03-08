<template>
  <div id="app">
    <HelloWorld msg="Hello Vju in CodeSandbox!" />

    <Trying />
  </div>
</template>


<script>
import HelloWorld from "./components/HelloWorld";
import Trying from "./components/Trying";

export default {
  name: "App",
  components: {
    HelloWorld,
    Trying,
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
  margin-top: 60px;
}
</style>
