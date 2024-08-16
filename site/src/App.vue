<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <MainFolder msg="Welcome to Your Vue.js App"/>
</template>

<script>
import MainFolder from './components/MainFolder.vue'

export default {
  name: 'App',
  components: {
    MainFolder
  }
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
}
</style>
