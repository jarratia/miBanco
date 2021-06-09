<template>
  <div class="container">
    <Titulo texto="Mi banco en Vue CLI" />
    <Cuenta />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Titulo from './components/Titulo';
import Cuenta from './components/Cuenta';


export default {
  name: 'App',
  components: {
    Titulo,
    Cuenta
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
