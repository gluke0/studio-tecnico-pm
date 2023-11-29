<script>

export default {
  name: "Services",
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
        <div class="services">

            <div class="box-service mt-0">
                <h4 class="text-uppercase ser-title">ufficio tecnico</h4>
                <div class="d-flex justify-content-around wrap">
                    <div class="d-flex justify-content-center align-items-center">
                        <img class="imgser" src="/img/ufficio.webp/" alt="">
                    </div>
                    <span class="single-service d-flex align-items-center">
                        Offriamo servizi di progettazione 3D e 2D che abbracciano diversi settori, dal meccanico al design. La nostra competenza ci permette di realizzare progetti personalizzati in co-design con il cliente, coinvolgendolo attivamente in ogni fase di sviluppo fino al completamento del progetto.
                    </span>
                </div>
            </div>

            <div class="box-service">
                <h4 class="text-uppercase ser-title">prototipi</h4>
                <div class="d-flex justify-content-around wrap">
                    <span class="single-service d-flex align-items-center">
                        Realizzazione fusioni prototipali grezze e/o lavorate e piccole serie per valutazioni tecnico-meccaniche del cliente
                    </span>
                    <div class="d-flex justify-content-center align-items-center">
                        <img class="imgser" src="/img/prototipi.webp/" alt="">
                    </div>
                </div>
            </div>

            <div class="box-service">
                <h4 class="text-uppercase ser-title">prototipazione rapida</h4>
                <div class="d-flex justify-content-around wrap">
                    <div class="d-flex justify-content-center align-items-center">
                        <img class="imgser" src="/img/prot-rapida.webp/" alt="">
                    </div>
                    <span class="single-service d-flex align-items-center">
                        Grazie a questa tecnologia siamo in grado di realizzare prototipi senza il costo di attrezzature in modo che il cliente possa già vedere fisicamente l'oggetto e valutarlo senza incappare in costi stampo magari da rivedere
                    </span>
                </div>
            </div>

            <div class="box-service">
                <h4 class="text-uppercase ser-title">stampi</h4>
                <div class="d-flex justify-content-around wrap">
                    <span class="single-service d-flex align-items-center">
                        Siamo in grado di gestire varie tipologie di stampo; dal polistirolo al pressofuso, dal modello in legno alla conchiglia in gravità. 
                    </span>
                    <div class="d-flex justify-content-center align-items-center">
                        <img class="imgser" src="/img/stampi.webp/" alt="">
                    </div>
                </div>
            </div>

            <div class="box-service">
                <h4 class="text-uppercase ser-title">reverse engineering</h4>
                <div class="d-flex justify-content-around wrap">
                    <div class="d-flex justify-content-center align-items-center">
                        <img class="imgser" src="/img/reverse.webp/" alt="">
                    </div>
                    <span class="single-service d-flex align-items-center">
                        Ricostruzione file 3D a partire da digitalizzazione di oggetti con Scanner 3D 
                    </span>
                </div>
            </div>

            <div class="box-service">
                <h4 class="text-uppercase ser-title">lavorazioni meccaniche di precisione</h4>
                <div class="d-flex justify-content-around wrap">
                    <span class="single-service d-flex align-items-center">
                        Eseguiamo lavorazioni meccaniche di precisione. La nostra esperienza e un importante Know-how ci rendono il partner ideale per qualsiasi realtà
                    </span>
                    <div class="d-flex justify-content-center align-items-center">
                        <img class="imgser" src="/img/precision.webp/" alt="">
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<style lang="scss">
@import '../../style/main.scss';

.services{
    width: 70%;
}

.ser-title{
    font-weight: bolder;
    font-style: italic;
    font-size: 2rem;
}

.box-service:hover{
    -webkit-box-shadow: 0px 10px 13px -5px, 7px 7px 50px 10px rgba(155, 183, 190, 0.67); 
    box-shadow: 0px 10px 13px -5px, 7px 7px 50px 10px rgba(155, 183, 190, 0.67);

}

.box-service{
    margin-top: 2rem;
    padding: 2rem;
    background-color: rgb(175, 182, 182);
}

.single-service{
    width: 50%;
}

.imgser {
  aspect-ratio: 1;
}


</style>
