<script setup>
defineProps({
  btnString: String,
})
</script>

<template>
    <button>{{ btnString }}</button>
</template>

<style lang="scss" scoped>
    button {
        padding-block: 4.5em;
        
        &:hover {
            border-bottom: 5px solid #0282F9;
            color: #0282F9;
            padding-bottom: calc(4.5em - 5px);
        }
    }
</style>