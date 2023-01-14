<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)

</script>

<template>
  <h2>Netflix2</h2>
  
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <h1>Hallo, das ist eine Netflix Seite</h1>
  </div>
</template>

<style >
@import "../assets/style/style.css";
</style>


