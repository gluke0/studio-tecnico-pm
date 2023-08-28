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
  <div class="container-lg">
    <div class="d-flex justify-content-between">
      <div class="logodiv">
        <img src="../../public/img/header/logo.webp" alt="Studio Tecnico Pedrini Logo">
      </div>
      <div class="menudiv">
        <ul class="d-flex justify-content-around">
          <li class="ms-4">Chi Siamo</li>
          <li class="ms-4">Servizi</li>
          <li class="ms-4">Dove Siamo</li>
          <li class="ms-4">Contatti</li>
        </ul>
      </div>
    </div>
  </div>
    
</template>

<style lang="scss">

img{
  width: 100%;
}

.logodiv{
  width: 25%;
}

.menudiv{
  width: 75%;
}



</style>