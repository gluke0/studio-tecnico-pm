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
  <div class="">
    <div class="">
      <div class="menudiv">
        <ul class="d-flex justify-content-around">
          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="">Chi siamo</a></li>
          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="">Servizi</a></li>
          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="">Contatti</a></li>
        </ul>
      </div>
      <div class="logodiv d-flex justify-content-center container">
        <img src="../../public/img/header/logonobg.svg" alt="Studio Tecnico Pedrini Logo">
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
  width: 100%;
  margin: auto;
  background-color: #4c6e8d;
  font-size: 1.5rem;
  height: 5rem;
}



</style>