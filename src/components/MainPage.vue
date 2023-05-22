<script>
import Jumbo from './Jumbo.vue';
import CurrentSeries from './CurrentSeries.vue';
import comicsJSON from '../json/dc-comics.json';

export default {
    data() {
        return {
            comic: comicsJSON,
        }
    },

    components: {
        Jumbo,
        CurrentSeries,
    }
}
</script>

<template>
    <main>
        <Jumbo />
        <div id="tagMid">CURRENT SERIES</div>
        <div id="divCard">
            <CurrentSeries v-for="cardComics in comic"
            :thumb="cardComics.thumb"
            :price="cardComics.price"
            :series="cardComics.series"
            :type="cardComics.type"
            />
        </div>
        <a href="#">LOAD MORE</a>
    </main>
    
</template>

<style lang="scss" scoped>
@import 'style.scss';
    main {
        position: relative;
        background-color: #1C1C1C;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    #tagMid {
        position: absolute;
        z-index: 1;
        padding: 1em;
        background-color: $primary-color;
        color: #fff;
        top: calc(540px - 1.5em);
        left: 0;
    }
    #divCard {
        display: flex;
        flex-wrap: wrap;
        padding: 3em 1em 2em 1em;
        gap: 1em;
        row-gap: 2em;
    }
    a {
        background-color: $primary-color;
        padding: 1em 4em;
        font-weight: bold;
        color: #fff;
        margin-block: 2em;
    }
</style>