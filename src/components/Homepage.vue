<template>
  <div class="hello">
    <div class="jumbotron img-fluid viewporth">
      <div class="container text-center viewportText">
        <div class="my-5">
          <h1 id="text-shadow-dark" class="display-5 text-white">Space Rangers</h1>      
          <hr class="my-4" />
          <p id="text-shadow-dark" class="lead text-white">From a space nerd, for the space nerds.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {name: "Homepage"};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#text-shadow-dark {
  text-shadow: 1px 1px 1px black;
}
.marketingImage {
  height: 15rem;
}
.jumbotron {
  background: #282c2b url("../assets/rocketdownrange.webp") no-repeat center center/cover;
  background-attachment: fixed;
  max-width: 100%;
  height: auto;
}

@media only screen and (max-width: 720px) {
  .jumbotron{
    background-attachment: unset;
  }
}

.viewporth {
  height: 90vh;
  width: 100%;
}
.viewportText {
  align-items: center;
  justify-content: center;
  text-align: center;
  vertical-align: middle;
}
.width-limit {
  max-width: 1632px;
  margin: auto;
}
</style>
