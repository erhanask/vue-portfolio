<template>
  <div>
    <h1 class="colorized-red">Deneme</h1>
    {{ msg }}
  </div>
</template>

<script>
export default {
  name: "Trying",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 20px 0 0;
  padding: 1rem;
}

.colorized-red {
  color: white;
  background-color: rgb(240, 0, 0);
}
</style>
