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
    <div class="d-flex justify-content-between">
      <div>
        <ul class="">
          <li class="ms-4"><a href="">Chi siamo</a></li>
          <li class="ms-4"><a href="">Servizi</a></li>
          <li class="ms-4"><a href="">Dove Siamo</a></li>
          <li class="ms-4"><a href="">Contatti</a></li>
        </ul>
      </div>
      <div>
        <ul class="">
          <a target="_blank" href="https://www.facebook.com/Studio%20tecnico%20Pedrini"><i class="fa-brands fa-square-facebook"></i></a>
        </ul>
      </div>
      <div>
        <ul class="">
          <li class="ms-4"><a href="">Chi siamo</a></li>
          <li class="ms-4"><a href="">Servizi</a></li>
          <li class="ms-4"><a href="">Dove Siamo</a></li>
          <li class="ms-4"><a href="">Contatti</a></li>
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