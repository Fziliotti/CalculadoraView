<template>
  <main>
    <div id="app">
      <Calculator />
    </div>
    <Rodape />
  </main>

</template>

<script>
  import Calculator from './components/Calculator.vue'
  import Rodape from './components/Rodape.vue'

  export default {
    name: 'app',
    components: {
      Calculator,
      Rodape
    }
  }
</script>

<style>
/* RESET */
html{
  box-sizing: border-box;
  line-height: 1.6;  /*Materialize*/
}

*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: inherit; 
}

body{
  background-color: #222;

}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  position: absolute;
  left: 50%;
  top: 40%;
  transform: translate(-50%, -50%);
}
</style>
