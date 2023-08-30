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
  <div class="container">
    <div class="">
      <div>
        <ul class="d-flex justify-content-center">
          <li class=""><a href="">Chi siamo</a></li>
          <li class="ms-4"><a href="">Servizi</a></li>
          <li class="ms-4"><a href="">Contatti</a></li>
        </ul>
      </div>
      <div>
        <ul class="d-flex justify-content-center">
          <span>Studio Tecnico Pedrini - 2023</span>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import '../style/main.scss';

.fa-brands{
  font-size: 4rem;
  color: #22313f;
}
</style>