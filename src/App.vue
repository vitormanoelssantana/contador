<script setup>
import { ref } from 'vue';

let contador = ref(0);


function incrementar() {
  contador.value++
}
function decrementar() {
  contador.value--
}
function resetar() {
  contador = 0;
}
if (contador = 1) {
  contador = 0;
} else {
  contador.value--
}

</script>
<template>
  <h1>Contador</h1>
  <p>Contador: {{ contador }}</p>
  <button @click="decrementar"> - </button>
  <button @click="incrementar"> + </button>
  <button @click="resetar"> Resetar </button>
</template>
<style scoped ></style>
