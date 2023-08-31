<script>

export default {
  name: "Footer",
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
    <div class="foot">
      <div class="">
        <ul class="d-flex justify-content-center">
          <li><a class="text-decoration-none text-dark" href="">Chi siamo</a></li>
          <li class="ms-4"><a class="text-decoration-none text-dark" href="">Servizi</a></li>
          <li class="ms-4"><a class="text-decoration-none text-dark" href="">Contatti</a></li>
        </ul>
      </div>
      <div>
        <ul class="d-flex justify-content-center credit">
          <span>Studio Tecnico Pedrini - 2023</span>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import '../style/main.scss';

.foot{
  width: 100%;
  background-color: #4c6e8d;
  padding: 2rem;
}

.credit{
  font-size: smaller;
  font-style: italic;
}


</style>