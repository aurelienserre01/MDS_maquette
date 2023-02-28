<script setup lang="ts">
import HomeHero from './components/views/HomeHero.vue';
import HomeCampus from './components/views/HomeCampus.vue';
import NavBar from './components/Utils/NavBar.vue';
</script>

<template>
    <NavBar />
    <HomeHero />
    <HomeCampus />
</template>

<style scoped>
body{
  background-color: #F9FBFC;
}
</style>
