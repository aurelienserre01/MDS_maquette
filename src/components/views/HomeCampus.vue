<template>
        <h1 class="text-center font-bold text-xl uppercase text-[#29B7C5]">des campus partout en france</h1>
        <div class="flex justify-around w-[60%] mt-14 mr-auto ml-auto">
            <LogoAndTitle v-for="src in srcs" :key="src" :src=src :etudiant="2000" />
        </div>
</template>
<script setup lang="ts">
import LogoAndTitle from '../Utils/LogoAndTitle.vue';
const srcs: string[] = ["src\\assets\\images\\villes\\lyon.png",'src\\assets\\images\\villes\\paris.png','src\\assets\\images\\villes\\annecy.png','src\\assets\\images\\villes\\nantes.png']
</script>