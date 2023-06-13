<script setup>
const props = defineProps ({
    text: String 
})
</script>

<template>
    <button>{{ props.text }}</button>
</template>

<style scoped>
button {
    background-color: rgb(226, 153, 245);
    padding: 9px 6px;
    border: 1px solid #f5c2ff;
    border-radius: 12px;
    color: white;
    font-size: 1rem;
    margin: 0 5px;
    cursor: pointer;
}

button:hover {
background-color: rgb(186, 133, 247);
}
</style>