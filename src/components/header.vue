<script>

export default {
  name: "Header",
  data() {
    return {
    }
  },
  components: {
    
  },
}
</script>

<template>
  <div class="container">
    <div class="">
      <div class="menudiv">
        <ul class="d-flex justify-content-around">
          <li class="ms-4">Chi Siamo</li>
          <li class="ms-4">Servizi</li>
          <li class="ms-4">Dove Siamo</li>
          <li class="ms-4">Contatti</li>
        </ul>
      </div>
      <div class="logodiv d-flex justify-content-center">
        <img src="../../public/img/header/logo.webp" alt="Studio Tecnico Pedrini Logo">
      </div>
    </div>
  </div>
    
</template>

<style lang="scss">

@import '../style/main.scss';

img{
  width: 100%;
}

.logodiv{
  width: 80%;
  margin: auto;
}

.menudiv{
  width: 80%;
  margin: auto;
}



</style>