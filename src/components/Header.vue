<template>
  <div class="set-bg">
    <div
      id="carouselExampleControls"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="../assets/about_me.jpg"
            class="d-block w-100 h-auto"
            style="height: 17rem"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="../assets/about_me.jpg"
            class="d-block w-100 h-auto"
            style="height: 17rem"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="../assets/about_me.jpg"
            class="d-block w-100 h-auto"
            style="height: 17rem"
            alt="..."
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleControls"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
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
.colorized-red {
  color: white;
  background-color: rgb(240, 0, 0);
}

.set-bg {
  background-color: black;
}
</style>
