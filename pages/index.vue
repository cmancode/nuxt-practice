<template>
  <div class="container">
    <h1>Hola, soy Carlos Alberto Mantilla</h1>
    <h1>{{mensaje}}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mensaje: 'Aquí estamos probando...'
    }
  }
}
</script>

<style lang="scss">
.container{
  background: #000;
  height: 100vh;
    h1{
      position: relative;
      top: 40%;
      color: #fff;
      text-align: center;
    }
}
</style>
