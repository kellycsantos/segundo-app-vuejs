<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Bem vindo(a) a minha segunda aplicação Vue.js"/>
 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

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

body{
  background: #abdac5;
  }
</style>
