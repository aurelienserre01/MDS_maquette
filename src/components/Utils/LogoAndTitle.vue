<template>
    <div class="grid grid-rows-2 w-[175px] content-between items-center justify-items-center h-[100px]">
        <img class="w-[80%]" :src="src" alt="">
        <h4 class="text-center text-[#686868] uppercase font-bold leading-9 text-xl">{{ etudiant }} étudiants</h4>
    </div>
</template>
<script setup lang="ts">
defineProps<{
    src: string,
    etudiant: number
}>()
</script>