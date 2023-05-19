<script lang="js">
import Jumbo from './Jumbo.vue';
import CurrentSeries from './CurrentSeries.vue';
import comicsJSON from '../json/dc-comics.json';

export default {
    data() {
        return {
        comicsJSON: comicsJSON,
        }
    },

    components: {
        Jumbo,
        // CurrentSeries,
    }
}
</script>

<template>
    <Jumbo />
    <div>
        <CurrentSeries v-for="cardComics in comicsJSON"
        :thumb="cardComics.thumb"
        :price="cardComics.price"
        :series="cardComics.series"
        :type="cardComics.type"
        />
    </div>
</template>

<style lang="scss" scoped>
    div {
        background-color: #1C1C1C;
    }
</style>