<script>

export default {
  name: "Contacts",
  data() {
    return {
    }
  },
  components: {

    
  },
}
</script>

<template>

    <div class="container my-5">
        <div class="d-flex justify-content-around">
            <div class="icons d-flex row text-center">
                <a target="_blank" href=""><i class="fa-solid fa-location-dot"></i></a>
                
                <div> Via Italia, 4 </div>
                <div> Casale Cremasco - Vidolasco </div>
                <div> 26010 Cremona</div>
                
            </div>
            <div class="icons d-flex row text-center">
                <a target="_blank" class="p-0" href=""><i class="fa-solid fa-phone"></i></a>
                <span> +39 3494759312 </span>
            </div>
        </div>
        <div class="d-flex justify-content-around mt-5">
            <div class="icons d-flex row text-center">
                <a class="text-decoration-none" href="mailto:studiotecnicopedrini@gmail.com"><i class="fa-solid fa-envelope"></i></a>
                <a class="text-decoration-none text-dark" href="mailto:studiotecnicopedrini@gmail.com">studiotecnicopedrini@gmail.com</a>
            </div>
            <div class="icons d-flex row text-center">
                <a class="text-decoration-none" target="_blank" href="https://www.facebook.com/Studio%20tecnico%20Pedrini"><i class="fa-brands fa-square-facebook"></i></a>
                <a class="text-decoration-none text-dark" target="_blank" href="https://www.facebook.com/Studio%20tecnico%20Pedrini">Studio Tecnico Pedrini </a>
            </div>
            
        </div>
    </div>
</template>

<style lang="scss">
@import '../../style/main.scss';

.fa-brands, .fa-solid{
  font-size: 4rem;
  color: #22313f;
}

.icons{
    width: 50%;
}

</style>