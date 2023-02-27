<template>
    <button class="bg-[#29B7C5] rounded-full py-3 px-6 text-white font-bold">
        {{ message }}
    </button>
</template>
<script setup lang="ts">
defineProps<{
    message: string
}>()
</script>
<style scoped>
button{
    font-family: 'Anek Bangla';
    font-size: 14.35px;
}
</style>