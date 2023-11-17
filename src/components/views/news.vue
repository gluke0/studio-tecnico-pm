<script>

export default {
  name: "news",
  data() {
    return {
    }
  },
  components: {
    
  },
}
</script>

<template>
    
  <div class="container d-flex justify-content-center">

    <div class="content">
      <div class="news d-flex justify-content-center">

        <div class="single-news">

          single news

        </div>

      </div>

      <div class="sponsor d-flex justify-content-center">

        sponsor in a carousel

      </div>
    </div>

  </div>

</template>

<style lang="scss">
@import '../../style/main.scss';

.news, .sponsor{
  margin: 3rem 0rem;
}

.content{
  width: 75%;
}

.single-news{
  border: solid 1px black;
}

</style>