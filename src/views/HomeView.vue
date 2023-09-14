<script setup>
import { onMounted, reactive, ref } from 'vue';


onMounted(() => {
  fetch('https://rickandmortyapi.com/api/character')
  .then(response => response.json())
  .then(response => {
    console.log(response);
  })
})

</script>

<template>
  <main>

  </main>
</template>
