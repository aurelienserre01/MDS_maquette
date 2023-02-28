<template>
    <div class="card rounded-[20px] w-[277px] h-80 bg-white p-8">
        <div class="image">
            <img width="207" class="mr-auto ml-auto" :src="images" alt="">
        </div>
        <div class="date font-normal text-xs mt-5 mb-4">
            {{date}}
        </div>
        <div class="title font-bold w-[80%]">
            {{title}}
        </div>
    </div>
</template>
<script setup lang="ts">
defineProps<{
    title: string,
    date: string,
    images: string
}>()
</script>
<style scoped>
.date {
    font-size: 14px;
    line-height: 25px;
}
</style>