<template>
    <div style="height: 48px;" class="fixed top-[7%] left-0 right-0 w-screen flex justify-around">
        <div>
            <img src="..\assets\images\logo_mds.png" alt="Logo MDS">
        </div>
        <div class="content-center flex w-4/12 justify-evenly">
            <a href="#" class="text-black px-3 py-2 text-sm font-bold">Accueil</a>
            <a href="#" class="text-[#A5A5A5]  px-3 py-2 text-sm font-bold">Les programmes</a>
            <a href="#" class="text-[#A5A5A5]  px-3 py-2 text-sm font-bold">Notre blog</a>
        </div>
        <ButtonMDS message="M'inscrire" />
    </div>
</template>

<script setup lang="ts">
import ButtonMDS from './Utils/ButtonMDS.vue';


</script>
<style scoped></style>