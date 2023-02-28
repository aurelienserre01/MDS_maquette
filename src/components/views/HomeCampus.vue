<template>
        <h3 class="text-center font-bold uppercase text-[#29B7C5]">des campus partout en france</h3>
        <div class="flex justify-around w-[50%] mt-14 mr-auto ml-auto">
            <LogoAndTitle v-for="src in srcs" :key="src" :src=src :etudiant="2000" />
        </div>
</template>
<script setup lang="ts">
import LogoAndTitle from '../Utils/LogoAndTitle.vue';
import lyon from '@/assets/images/villes/lyon.png'
import paris from '@/assets/images/villes/paris.png'
import annecy from '@/assets/images/villes/annecy.png'
import nantes from '@/assets/images/villes/nantes.png'
const srcs: string[] = [lyon,paris,annecy,nantes]
</script>
<style scoped>
h3{
    font-size: 20px;
    line-height: 37.3px;
}
</style>