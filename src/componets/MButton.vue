<script setup>
const props = defineProps({
    texto: String
})
</script>

<template>
    <button>{{ props.texto }}</button>
</template>

<style scoped>
button {
    background-color: rgb(92, 199, 218);
    color: aliceblue;
    font-size: 1.1rem;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 5px 10px;
    cursor: pointer;
}

button:hover{
    background-color: darkblue;
}
</style>