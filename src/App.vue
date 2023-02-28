<script setup lang="ts">
import HomeHero from './components/views/HomeHero.vue';
import HomeCampus from './components/views/HomeCampus.vue';
import NavBar from './components/Utils/NavBar.vue';
import HomeDomains from './components/views/HomeDomains.vue';
import HomeBlog from './components/views/HomeBlog.vue';
</script>

<template>
    <NavBar />
    <HomeHero />
    <HomeCampus />
    <HomeDomains />
    <HomeBlog />
</template>

<style scoped>
body{
  background-color: #F9FBFC;
}
</style>
