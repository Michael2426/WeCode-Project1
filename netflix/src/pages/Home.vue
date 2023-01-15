<script>
const msg = "Hallo Welt";
const rawHtml = "<p>Ich bin ein Text</p>";
// const dynamicId = ref(12);

export default {
    name: 'home',
    components: {},
};
</script>

<template>
    <div class="card">
        <h1>Home</h1>
        <span style="color:blue">Message: {{ msg }}</span>
        <p>Using text interpolation: {{ rawHtml }}</p>
        <p>Using v-html directive: <span v-html="rawHtml"></span></p>
        <div v-bind:id="dynamicId"></div>
        <div :id="dynamicId"></div><!-- shortForm -->    
    </div>
</template>

<style>
@import "../assets/style/style.css";
</style>