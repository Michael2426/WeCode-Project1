<script setup>
//  import { ref } from 'vue'

// defineProps({
//   msg: String,
// })

// const count = ref(0)

const username = string;
const password = string;
const msg = string;


//sConnectionString = "Hier kommen die Anmeldedaten rein";

try {
  if(username === michaelr)
  {
    if(password === 123456)
    {
      msg = "Login successful";
      connect 
    }
    else
    {
      msg = "Login failed";
    }
  }
  else
  {
    msg = "Login failed";
  }
} catch (exceptionVar) {
  console.log(typeof(exceptionVar) + ":" + ex);
} finally {
  console.log(msg);
}
</script>

<template>
  <h1>{{ msg }}</h1>
  <h1>Netflix</h1>
  <header>
    <a href="https://www.netflix.com/de/">Netflix-Header</a>
  </header>
  <main>
    <a href="https://www.netflix.com/de/">Netflix-Main</a>
  </main>
  <footer>
    <a href="https://www.netflix.com/de/">Netflix-Footer</a>
  </footer>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>

    <a href="https://www.netflix.com/de/">
      <img src="../../public/images/Netflix_Logo.png"/>
    </a>
    <div class="read-the-docs">
      <a href="https://www.netflix.com/de/">Netflix</a>
    </div>
  </div>  
</template>

<style scoped>
.read-the-docs {
  color: #150;
}
</style>
