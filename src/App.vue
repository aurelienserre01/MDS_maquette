<script setup lang="ts">
import HomeHero from './components/views/HomeHero.vue';
import HomeCampus from './components/views/HomeCampus.vue';
import NavBar from './components/Utils/NavBar.vue';
import HomeDomains from './components/views/HomeDomains.vue';
</script>

<template>
    <NavBar />
    <HomeHero />
    <HomeCampus />
    <HomeDomains />
</template>

<style scoped>
body{
  background-color: #F9FBFC;
}
</style>
