<template>
  <div id="top-level-container">
    <img alt="Orange Potato Productions Logo" src="../assets/logo_light.png">
  </div>
</template>

<script>

export default {
  name: "Container",
  components: {}
}
</script>

<style scoped>

#top-level-container {
  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: center;
  width: 100vw;
  height: 100vh;
}

</style>