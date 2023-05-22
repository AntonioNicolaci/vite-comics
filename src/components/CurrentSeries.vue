<script>
export default {
    props: {
        thumb: String,
        price: String,
        series: String,
        type: String,
    }    
}
</script>

<template>
    <div>
        <img :src="thumb" :alt="series">
        <span>{{ series }}</span>
    </div>
</template>

<style lang="scss" scoped>
    div {
        display: inline;
        width: calc(100% / 6 - 1em)
    }
    img {
        width: 100%;
        height: 100%;
    }
    span {
        color: #fff;
    }
</style>