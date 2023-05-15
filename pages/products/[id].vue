<template>
    <div>
<p>Prduct details for {{ id  }}</p>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat explicabo sequi dolorem? Eaque consectetur ut voluptas praesentium, sunt repellendus? Possimus.</p>
    </div>
</template>

<script setup>

const {id} = useRoute().params

definePageMeta({
    layout:'products'
})
</script>

<style scoped>
 
</style>