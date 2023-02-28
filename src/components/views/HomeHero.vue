<template>
    <div class="w-[1134px] mr-auto ml-auto mb-24">
        <h1 class="w-[75%] mr-auto ml-auto font-extrabold text-center tracking-tighter text-[#07052F]">La meilleure école des métiers du digital</h1>
        <div class="mr-auto ml-auto w-fit mt-12">
            <ButtonMDS message="Appelez-nous" />
        </div>
        <div class="flex justify-evenly w-[80%] mr-auto ml-auto">
            <img :src="rectangle1" alt="">
            <img :src="rectangle2" class="mt-36" alt="">
            <img :src="rectangle3" class="mt-36" alt="">
            <img :src="rectangle4" alt="">            
        </div>
    </div>
</template>
<script setup lang="ts">
import ButtonMDS from '../Utils/ButtonMDS.vue';
import rectangle1 from '@/assets/images/profiles/Rectangle1.svg'
import rectangle2 from '@/assets/images/profiles/Rectangle2.svg'
import rectangle3 from '@/assets/images/profiles/Rectangle3.svg'
import rectangle4 from '@/assets/images/profiles/Rectangle4.svg'

</script>
<style scoped>
h1{
    font-size: 70px;
    line-height: 70px;
}

</style>