<script setup>
import HelloWorld from './components/HelloWorld.vue'
import AppHeader from "@/components/AppHeader.vue";
</script>



<script>
export default {
  components: {
 AppHeader,
 },
}
</script>
<template>
<h1>Hello, Vue.js!</h1>

<div id="app">
<AppHeader />
 <div class="container mt-3">
 <router-view />
 </div>
 </div>
</template>


<style>
.page {
max-width: 400px;
margin: auto;
}
</style>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
