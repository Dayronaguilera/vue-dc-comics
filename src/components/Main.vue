<template> 
    <div class="bg-main">
        <div class="container">
            <div class="row">
                <Card
                v-for="(element, index) in comics"
                :key="index"
                :thumb="element.thumb"
                :price="element.price"
                :title="element.series"
                />
            </div>
        </div>
    </div>
</template>

<script>

import Card from './Card.vue'; //importiamo il nostro components card

export default {
    name: "Main",
    components: { //elenchiamo il nostro components
    Card,
    },
    props: { //ci mettiamo in ascolto e chiediamo un array
        comics: Array,
    },
    created() { //creiamo un console.log per verificare che i dati stanno arrivando!
        console.log(this.comics);
    },
};

</script>

<style lang="scss" scoped>
    .bg-main{
        color: white;
        background: black;
        .row{
            display: flex;
            flex-wrap: wrap; 
            padding: 30px;
        }
    }

</style>