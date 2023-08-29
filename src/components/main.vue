<script>
import whoarewe from './views/whoarewe.vue';
import services from './views/services.vue';

export default {
  name: "Main",
  data() {
    return {
    }
  },
  components: {
    whoarewe,
    services,
    
  },
}
</script>

<template>
    
  <whoarewe></whoarewe>
  <services></services>

</template>

<style lang="scss">

</style>