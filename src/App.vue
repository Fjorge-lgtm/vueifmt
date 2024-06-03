<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Menu msg="Menu do Vue.js"/>
  <Formulario msg="Componente utilizado  para  o Formulário"/>
  <BarraLateral msg="Componete utilizado para  a Barra Lateral "/>
  <Footer msg="Componente utilizado para nnnno Rodapé "/>
</template>

<script>

import Menu from './components/Menu.vue';
import Formulario from './components/Formulario.vue';
import BarraLateral from './components/BarraLateral.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Menu,
    Formulario,
    BarraLateral,
    Footer,
   }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #081175;
  margin-top: 60px;
}
</style>
