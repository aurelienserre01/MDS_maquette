<template>
    <div class="formes w-[70%] ml-auto mr-auto h-[495px] mb-20">
        <h2 class="title text-center font-extrabold w-[70%] mr-auto ml-auto pt-16 text-white">Entre ton e-mail pour recevoir
            le programme de l’école</h2>
        <p class="text-center text-white w-[30%] mr-auto ml-auto mt-7">Nous t’enverrons le programme complet, et quelqu’un
            prendra contact avec toi pour savoir tes besoins</p>
        <div class="bg-white w-fit p-1 rounded-full mr-auto ml-auto mt-16 ">
            <input class="mr-10 ml-10" type="text" placeholder="Entre ton address e-mail ici" >
            <ButtonMDS message="Envoyer" />
        </div>
    </div>
</template>
<script setup lang="ts">
import ButtonMDS from '../Utils/ButtonMDS.vue';
</script>
<style scoped>
.formes {
    background-image: url('../../assets/images/Rectangle7.svg');
    background-repeat: no-repeat;
}

h2 {
    font-size: 41.4px;
    line-height: 50px;
}

p{
    font-size: 15px;
    line-height: 20px;
}
</style>