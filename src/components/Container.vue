<template>
  <div class="top-level-container">
    <img alt="Orange Potato Productions Logo" src="../assets/logo_light.png">
    <div class="text">info@orangepotato.productions</div>
  </div>
</template>

<script>

export default {
  name: "Container",
  components: {}
}
</script>

<style scoped>
.top-level-container {
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-content: center;
  padding: 10%;
}
.text {
  padding-top: 20px;
  font-size: 1.3rem;

}
</style>