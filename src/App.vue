<template>
  <PortadaComponente></PortadaComponente>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Primeros pasos en Vue"/>
  <br>
  <MiComponente></MiComponente>
  <DatosComponente></DatosComponente>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiComponente from './components/MiComponente.vue'
import DatosComponente from './components/DatosComponente.vue'
import PortadaComponente from './components/PortadaComponente.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MiComponente,
    DatosComponente,
    PortadaComponente
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
