<script lang="js">
export default {
    
}

defineProps({
        thumb: String, // link immagine
        price: String, // prezzo
        series: String, // serie del fumetto
        type: String, // tipo di fumetto
    })
</script>

<template>
    <div>
        <img :src="thumb" :alt="series">
    </div>
</template>

<style lang="" scoped>
    
</style>