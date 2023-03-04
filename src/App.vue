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
.grid-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100vh;
}

.grid-item {
  width: 15%;
}

img {
  display: block;
  text-align: center;
}

</style>
