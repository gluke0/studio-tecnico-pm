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
        <ul class="d-flex justify-content-around py-4">
          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="">Chi siamo</a></li>

          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="">Cosa facciamo</a></li>

          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="">Contatti</a></li>
        </ul>
      </div>
      <div class="logodiv d-flex justify-content-center container">

        <img src="/img/header/oldlogo.webp" alt="Studio Tecnico Pedrini Logo">

      </div>
    </div>
  </div>
    
</template>

<style lang="scss">

@import '../style/main.scss';

img{
  width: 70%;
}

.logodiv{
  width: 100%;
  margin: auto;.
}

.menudiv{
  width: 100%;
  margin: auto;
  background-color: rgb(96, 178, 249);
  font-size: 1.5rem;
  height: 5rem;
}



</style>