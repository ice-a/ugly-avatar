<template>
  <FaceGenerator/>

</template>

<script>
import FaceGenerator from './views/FaceGenerator.vue'

export default {
  components: {FaceGenerator},
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;

  .footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
  }
}
</style>
