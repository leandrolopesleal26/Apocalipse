<template>
  <img class="logo" alt="Pergaminho Selado" src="./assets/selado.png">
  <HelloWorld msg="Bem vindo ao Estudo do livro de Apocalipse"/>
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
  font-family: Avenir, Helvetica, Arial, sans-serif, ;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}
.logo{
  height: 90%;
  width: 90%;
  
}
</style>
