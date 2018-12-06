<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo2.svg" id="homeLogo">
    <HelloWorld msg="Welcome to drcoder"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
  #homeLogo {
    width: 100px;
    height: auto;
  }
</style>
