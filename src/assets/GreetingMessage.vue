<script setup>
// const props = defineProps({
//     firstName: String,
//     lastName: String
// })
// ---------------------
// import { defineEmits } from 'vue';

// const emits = defineEmits(['greet'])

// function greetAlert() {
//     emits('greet','Noval Rialan')
// }
// ---------------------
import { ref } from 'vue'
let joke = ref({})

await fetch('https://api.chucknorris.io/jokes/random')
    .then((response) => response.json())
.then((data)=> joke = data)
</script>

<template>
    <!-- <h2>Hello {{ props.firstName }} {{ props.lastName }}</h2> -->
    <!-- <button @click="greetAlert">Greet Me</button> -->
    <p>{{ joke.value }}</p>
</template>