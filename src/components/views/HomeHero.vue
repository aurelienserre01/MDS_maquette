<template>
    <div class="w-[1134px] mr-auto ml-auto mb-24">
        <h1 class="w-[75%] mr-auto ml-auto font-extrabold text-center tracking-tighter text-[#07052F]">La meilleure école des métiers du digital</h1>
        <div class="mr-auto ml-auto w-fit mt-12">
            <ButtonMDS message="Appelez-nous" />
        </div>
        <div class="flex justify-evenly w-[80%] mr-auto ml-auto">
            <img :src="rectangle1" alt="">
            <img src="..\..\assets\images\profiles\rectangle2.svg" class="mt-36" alt="">
            <img src="..\..\assets\images\profiles\rectangle3.svg" class="mt-36" alt="">
            <img src="..\..\assets\images\profiles\rectangle4.svg" alt="">            
        </div>
    </div>
</template>
<script setup lang="ts">
import ButtonMDS from '../Utils/ButtonMDS.vue';
import rectangle1 from '@/assets/images/profiles/rectangle1.svg'

</script>
<style scoped>
h1{
    font-size: 70px;
    line-height: 70px;
}

</style>