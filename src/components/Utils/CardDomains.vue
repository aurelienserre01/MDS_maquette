<template>
    <div class="card rounded-[20px] w-[277px] h-80 bg-white p-7">
        <div class="logo pt-4 w-14 h-14 bg-[#29B7C5] rounded-lg">
            <img class="m-auto" width="31" height="31" :src="icon" alt="">
        </div>
        <div class="text mt-5">
            <span class="title font-bold text-lg text-black"> {{ title }}</span>
            <p class="font-normal mt-1 w-[90%]">{{ content }}</p>
        </div>
        <div class="absolute bottom-4">
            <span class="font-bold leading-5 text-sm">Découvrir</span>
        </div>
        
    </div>
</template>
<script setup lang="ts">
defineProps<{
    title: string,
    content: string,
    icon: string
}>()
</script>
<style scoped>
.card{
    box-shadow: 0px 0px 30px rgba(0, 0, 0, 0.1);
}

p{
    line-height: 20px;

}
</style>