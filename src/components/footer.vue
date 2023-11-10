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

          <li><a class="text-decoration-none text-dark" href=""> Chi siamo </a></li>

          <li class="ms-4"><a class="text-decoration-none text-dark" href=""> Cosa facciamo</a></li>

          <li class="ms-4"><a class="text-decoration-none text-dark" href=""> Come contattarci </a></li>

        </ul>
      </div>
      <div>
        <ul class="d-flex justify-content-center credit">
          <span> Studio Tecnico Pedrini </span>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import '../style/main.scss';

.foot{
  width: 100%;
  background-color: rgb(96, 178, 249);  
  padding: 2rem;
}

.credit{
  font-size: smaller;
  font-style: italic;
}


</style>