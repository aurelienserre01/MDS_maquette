<template>
        <h3 class="text-center font-bold uppercase text-[#29B7C5]">des campus partout en france</h3>
        <div class="flex justify-around w-[50%] mt-14 mr-auto ml-auto">
            <LogoAndTitle v-for="src in srcs" :key="src" :src=src :etudiant="2000" />
        </div>
</template>
<script setup lang="ts">
import LogoAndTitle from '../Utils/LogoAndTitle.vue';
const srcs: string[] = ["src\\assets\\images\\villes\\lyon.png",'src\\assets\\images\\villes\\paris.png','src\\assets\\images\\villes\\annecy.png','src\\assets\\images\\villes\\nantes.png']
</script>
<style scoped>
h3{
    font-size: 20px;
    line-height: 37.3px;
}
</style>