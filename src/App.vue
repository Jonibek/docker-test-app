<template>
  <div class="grid-container">
    <img class="grid-item " alt="Docker logo" src="./assets/logo.png">
    <h1>I LOVE VUE & DOCKER</h1>
    <img class="grid-item" alt="Vue logo" src="./assets/docker.svg">
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  max-height: 100vh;
}

.grid-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100vh;
  padding-top: 250px;
}

.grid-item {
  width: 15%;
}

img {
  display: block;
  text-align: center;
}

</style>
