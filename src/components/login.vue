<template>
  <form class="form">
    <h1>Registrarse</h1>
    <input type="text">
    <input type="password">
    <button>Continuar</button>
  </form>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
.form{
  width: 20%;
  margin: auto;
  display: flex;
  flex-direction: column;
  height: 40vh;
}
input{
  padding: 0px 4%;
  margin-bottom:4% ;
}

@media screen and (max-width: 700px) {
  .form{
    width: 50%;
  }
}
</style>