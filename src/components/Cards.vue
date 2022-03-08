<template>
  <div class="w-100 bg-dark">
    <div class="container mt-4 bt-4">
      <div class="container text-white mt-3 mb-3">
        <h1>Example Title</h1>
        <div>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam similique
          perferendis iure nemo beatae voluptas dolores veritatis. Totam dolorum
          quod dolores? Consectetur beatae provident minima cumque at sint
          maxime atque.
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4 col-md-12 single-card">
          <div
            class="container mt-3 mb-3 shadow single-card-inner custom-border"
          >
            <div class="container text-white">
              <h3 class="m-2"><b>Example Title</b></h3>
              <ul class="list-group p-3" style="text-align: left">
                <li>Test</li>
                <li>Test2</li>
                <li>Test3</li>
                <li>Test4</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-12 single-card">
          <div
            class="container mt-3 mb-3 shadow single-card-inner custom-border"
          >
            <div class="container text-white">
              <h3 class="m-2"><b>Example Title</b></h3>
              <ul class="list-group p-3" style="text-align: left">
                <li>Test</li>
                <li>Test2</li>
                <li>Test3</li>
                <li>Test4</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-12 single-card">
          <div
            class="container mt-3 mb-3 shadow single-card-inner custom-border"
          >
            <div class="container text-white">
              <h3 class="m-2"><b>Example Title</b></h3>
              <ul class="list-group p-3" style="text-align: left">
                <li>Test</li>
                <li>Test2</li>
                <li>Test3</li>
                <li>Test4</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cards",
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

.single-card {
  margin-left: auto;
  margin-right: auto;
}

.custom-border {
  border: 1px solid gray;
  border-radius: 5px;
}

.colorized-red {
  color: white;
  background-color: rgb(240, 0, 0);
}

@media only screen and (max-width: 768px) {
  .single-card-inner {
    width: 50%;
  }
}
</style>
