<script>
import BtnHeader from './BtnHeader.vue';

export default {
    data() {
        return {
            btnArray: [
            {
                string: 'CHARACTERS',
                link: '#'
            },
            {
                string: 'COMICS',
                link: '#'
            },
            {
                string: 'MOVIE',
                link: '#'
            },
            {
                string: 'TV',
                link: '#'
            },
            {
                string: 'GAMES',
                link: '#'
            },
            {
                string: 'COLLECTIBLES',
                link: '#'
            },
            {
                string: 'VIDEOS',
                link: '#'
            },
            {
                string: 'FANS',
                link: '#'
            },
            {
                string: 'NEWS',
                link: '#'
            },
            {
                string: 'SHOP',
                link: '#'
            }
            ]
        }
    },
    
    components: {
        BtnHeader,
    }
}

</script>

<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="dc-logo">
        <div id="divButton">
            <BtnHeader v-for="btnString in btnArray"
            :btnString="btnString.string" 
            :link="btnString.link"/>
        </div>
    </header>
    
</template>

<style lang="scss" scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: fixed;
        background-color: #fff;
        width: 100%;
        z-index: 100;
    }
    #divButton {
        display: flex;
        gap: 30px;
    }
</style>