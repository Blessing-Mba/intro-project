<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import MainPart from './components/MainPart.vue';
import ButtonClick from './components/ButtonClick.vue';
</script>
 
<template>
 <div class="bg-white w-full h-full">
  <NavBar />
  <MainPart />
  <ButtonClick />
 </div>
  </template>

<script>


export default {
  components: {
    NavBar,
    MainPart,
    ButtonClick,
  }
}
</script>