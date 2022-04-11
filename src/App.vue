<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitoloComp></TitoloComp>
    <HeroComp></HeroComp>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TitoloComp from './components/TitoloComp.vue'
import HeroComp from './components/HeroComp.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    TitoloComp,
    HeroComp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
