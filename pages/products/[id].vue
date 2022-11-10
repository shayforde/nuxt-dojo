<template>
    <div>
        <h1>the product is {{ id }}</h1>
    </div>
</template>

<script setup>
const { id } = useRoute().params

// another comment 

definePageMeta({
    layout: 'products'
})
</script>

<style  scoped>

</style>