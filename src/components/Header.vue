<script>
import BtnHeader from './BtnHeader.vue';

export default {
    components: {
        BtnHeader,
    }
}

</script>

<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="dc-logo">
        <div id="divButton">
            <BtnHeader btnString="CHARACTERS" />
            <BtnHeader btnString="COMICS" />
            <BtnHeader btnString="MOVIE" />
            <BtnHeader btnString="TV" />
            <BtnHeader btnString="GAMES" />
            <BtnHeader btnString="COLLECTIBLES" />
            <BtnHeader btnString="VIDEOS" />
            <BtnHeader btnString="FANS" />
            <BtnHeader btnString="NEWS" />
            <BtnHeader btnString="SHOP" />
        </div>    
    </header>
    
</template>

<style lang="scss" scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    #divButton {
        display: flex;
        gap: 10px;
    }
</style>