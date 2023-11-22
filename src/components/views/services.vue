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
                <span class="single-service">
                    Offriamo servizi di progettazione 3D e 2D che abbracciano diversi settori, dal meccanico al design. La nostra competenza ci permette di realizzare progetti personalizzati in co-design con il cliente, coinvolgendolo attivamente in ogni fase di sviluppo fino al completamento del progetto.
                </span>
            </div>
            <div class="box-service">
                <h4 class="text-uppercase ser-title">prototipi</h4>
                <span class="single-service">
                    Realizzazione fusioni prototipali grezze e/o lavorate e piccole serie per valutazioni tecnico-meccaniche del cliente
                </span>
            </div>
            <div class="box-service">
                <h4 class="text-uppercase ser-title">prototipazione rapida</h4>
                <span class="single-service">
                    Grazie a questa tecnologia siamo in grado di realizzare prototipi senza il costo di attrezzature in modo che il cliente possa già vedere fisicamente l'oggetto e valutarlo senza incappare in costi stampo magari da rivedere
                </span>
            </div>
            <div class="box-service">
                <h4 class="text-uppercase ser-title">stampi</h4>
                <span class="single-service">
                    Siamo in grado di gestire varie tipologie di stampo; dal polistirolo al pressofuso, dal modello in legno alla conchiglia in gravità. 
                </span>
            </div>
            <div class="box-service">
                <h4 class="text-uppercase ser-title">reverse engineering</h4>
                <span class="single-service">
                    Ricostruzione file 3D a partire da digitalizzazione di oggetti con Scanner 3D 
                </span>
            </div>
            <div class="box-service">
                <h4 class="text-uppercase ser-title">lavorazioni meccaniche di precisione</h4>
                <span class="single-service mt-5">
                    Eseguiamo lavorazioni meccaniche di precisione. La nostra esperienza e un importante Know-how ci rendono il partner ideale per qualsiasi realtà
                </span>
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
    border: solid 3px grey;
    font-size: larger;
}

.box-service{
    margin-top: 2rem;
    padding: 2rem;
    background-color: rgb(175, 182, 182);
}


</style>