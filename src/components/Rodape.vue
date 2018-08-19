<template>
  <div class="rodape">
    <p>{{desenvolvedor}} - {{info}}</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        desenvolvedor: "Fabricio Ziliotti",
        info: "Training VueJs"
      }
    }
  }
</script>

<style scoped>
  .rodape{
    background-color: darkgrey;
    color: white;
    font-size: 1.8rem;
    position: absolute;
    width: 100%;
    bottom: 0;
    text-align: center;
    padding: 1.2rem;
  }
</style>
