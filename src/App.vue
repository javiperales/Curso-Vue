<template>
  <div id="app">
     <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Probando la template"/>
    <h4>Probando commit </h4>
    <br>
    
  </div>
  
</template>

<script>
//import Index from '../public/index.html'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    //Index
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
