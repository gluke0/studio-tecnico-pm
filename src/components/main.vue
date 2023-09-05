<script>
import whoarewe from './views/whoarewe.vue';
import services from './views/services.vue';
import news from './views/news.vue';
import contacts from './views/contacts.vue';


export default {
  name: "Main",
  data() {
    return {
    }
  },
  components: {
    whoarewe,
    services,
    news,
    contacts,
  },
}
</script>

<template>
    
  <whoarewe></whoarewe>
  <services></services>
  <news></news>
  <contacts></contacts>

</template>

<style lang="scss">
@import '../style/main.scss';
</style>