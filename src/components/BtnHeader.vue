<script>
export default {
    props: {
        btnString: String,
        link: String,
    }
}
</script>

<template>
    <a :href="link">{{ btnString }}</a>
</template>

<style lang="scss" scoped>
    a {
        --font-padding: 4em;
        padding-block: var(--font-padding);
        font-weight: bold;
        
        &:hover, &:active {
                border-bottom: 5px solid #0282F9;
                color: #0282F9;
                padding-bottom: calc(var(--font-padding) - 5px);
        }
    }
</style>