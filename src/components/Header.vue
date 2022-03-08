<template>
  <div>
    <div
      id="carouselExampleSlidesOnly"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="..." class="d-block w-100" alt="..." />
        </div>
        <div class="carousel-item">
          <img src="..." class="d-block w-100" alt="..." />
        </div>
        <div class="carousel-item">
          <img src="..." class="d-block w-100" alt="..." />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {},
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
