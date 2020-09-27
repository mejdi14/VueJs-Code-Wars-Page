<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/finger_cat.png"  width="300" height="400">
    <HelloWorld msg="you haven't done any code wars challange for today :'("/>
  </div>
</template>

<script>
import HelloWorld from './components/CatBlocker.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
