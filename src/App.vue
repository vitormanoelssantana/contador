<script setup>
import { ref } from 'vue';

const contador = ref(0);

function incrementar() {
  contador.value++
}
function decrementar() {
  contador.value--
}
</script>
<template>
  <h1>Contador</h1>
  <p>Contador: {{ contador }}</p>
  <button @click="decrementar"> - </button>
  <button @click="incrementar"> + </button>
</template>
<style scoped ></style>
