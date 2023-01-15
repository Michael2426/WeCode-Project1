<script setup>
import { ref, Text } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0);

const materials = [
  'Hydrogen',
  'Helium',
  'Lithium',
  'Beryllium'
];

</script>

<template>
  <h2>Netflix</h2>
  
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <hr/>
    <input :value="Username" @input="event => text = event.target.value">
    <input :value="Password" @input="event => text = event.target.value">
    <input v-model="text">
    <input v-model="textarea">
    <input v-model="select">
    <input type="checkbox">
    <input type="radio">

    <h1>Hallo, das ist eine Netflix Seite</h1>
    <div class="navbar">
      <div class="logo"/>
      <img src="../assets/vue.svg" alt="logo" />
      <h3>WeCode-Projects</h3>
      <div class="hamburger"/>
      <div class="placeholder"/>    
      <div class="content">        
        <nav>NavTitel</nav>
        <nav>NavTitel</nav>
        <nav>NavTitel</nav>
      </div>      
    </div>
  </div>
</template>

<style>
  @import "../assets/style/style.css";
</style>


