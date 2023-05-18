<script>
export default {
    nome: "SingoloFumetto",
    //questa sintassi non necessita di specificare la tipologia di dato importato" metodo 1 "
    // props:['dettagliOggetto'],

    //questa sintassi necessita la spiegazione basata sull'importazione di un oggetto" metodo 2 "
    props: {
        dettagliOggetto: Object
    }
}

</script>

<template>
    <!-- singolo fumetto  -->
    <div id="box-cards-collection">
        <div class="cards-collection">
            <img :src="dettagliOggetto.thumb" :alt="dettagliOggetto.series">
            <h4> {{ dettagliOggetto.series }} </h4>
        </div>
    </div>
</template>


<!-- sezione parametri di centratura degli elementi -->
<style lang="scss" scoped >
.container {}
</style>