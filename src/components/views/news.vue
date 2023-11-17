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
      <div class="news d-flex justify-content-between">

        <div class="single-news">

          single 

        </div>
        <div class="single-news">

          single 

        </div>
        <div class="single-news">

          single 

        </div>
        

      </div>

      <div class="sponsor d-flex justify-content-between">

        <div class="single-sponsor">

          single 

        </div>
        <div class="single-sponsor">

          single 

        </div>
        <div class="single-sponsor">

          single 

        </div>

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
  padding: 6rem 8rem;
  background-color: rgb(96, 178, 249);  
}

.single-sponsor{
  padding: 6rem 8rem;
  background-color: rgb(96, 178, 249);  
}

</style>