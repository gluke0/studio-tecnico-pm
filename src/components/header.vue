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
        <ul class="d-flex justify-content-around py-4 header">

          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="#whoarewe"> Chi siamo </a></li>

          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="#servicesservices"> Cosa facciamo </a></li>

          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="#newsnews"> Notizie </a></li>

          <li class=""><a class="text-decoration-none text-dark text-uppercase" href="#contactscontacts"> Come contattarci </a></li>
          
        </ul>
      </div>
      <div class="logodiv d-flex justify-content-center container pt-4">

        <img src="/img/header/pedrini.png" alt="Studio Tecnico Pedrini Logo">

      </div>
    </div>
  </div>
    
</template>

<style lang="scss">

@import '../style/main.scss';

img{
  width: 70%;
}

.header{
  font-weight: bold;
}

.logodiv{
  width: 100%;
  margin: auto;
}

.menudiv{
  width: 100%;
  margin: auto;
  background-color: rgb(96, 178, 249);
  font-size: 1.5rem;
  height: 5rem;
}

li:hover{
  transform: scale(1.1);
  cursor: pointer;
}


</style>