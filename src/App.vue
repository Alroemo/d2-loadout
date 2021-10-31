<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <loadout></loadout>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import loadout from './components/loadout.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    loadout
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
