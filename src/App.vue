<template>
  <div>
    <nav-bar></nav-bar>
    <div id="app">
      <page-heading></page-heading>  
      <img alt="Vue logo" src="./assets/logo.png">
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/nav-bar.vue'
import PageHeading from './components/page-heading.vue'

export default {
  name: 'app',
  components: {
    NavBar,PageHeading,HelloWorld}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
