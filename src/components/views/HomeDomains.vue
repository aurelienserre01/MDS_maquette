<script setup lang="ts">
import ButtonMDS from '../Utils/ButtonMDS.vue';
import CardDomains from '../Utils/CardDomains.vue';
const contents = [{
    title: 'Webmarketing',
    content: 'Classée la 2ème meilleure école de France dans ce domaine, le marketing digital est la spécialité de MyDigitalSchool',
    icon: 'src\\assets\\images\\icons\\Vector.svg'
},
{
    title: 'UI & UX Design',
    content: 'Classée la 2ème meilleure école de France dans ce domaine, le marketing digital est la spécialité de MyDigitalSchool',
    icon: 'src\\assets\\images\\icons\\Vector.svg'
},
{
    title: 'Programmation',
    content: 'Classée la 2ème meilleure école de France dans ce domaine, le marketing digital est la spécialité de MyDigitalSchool',
    icon: 'src\\assets\\images\\icons\\Vector.svg'
},
{
    title: 'Communication',
    content: 'Classée la 2ème meilleure école de France dans ce domaine, le marketing digital est la spécialité de MyDigitalSchool',
    icon: 'src\\assets\\images\\icons\\Vector.svg'
}
]
</script>
<template>
    <div class="mt-80">
        <h3 class="text-center font-bold uppercase text-[#29B7C5]">plusieurs spécialités</h3>
        <h2 class="text-center font-extrabold w-[35%] mr-auto ml-auto">Les domaines les plus demandés dans le digital</h2>
        <div class="flex justify-around w-[70%] mr-auto ml-auto mt-28">
            <CardDomains v-for="content in contents" :key="content.title" :title=content.title :content=content.content
                :icon="content.icon" />
        </div>
        <div class="mt-20 mr-auto ml-auto w-fit">
            <ButtonMDS message="Télécharger le programme" />
        </div>
              
    </div>
</template>

<style scoped>
h2 {
    font-size: 41.4px;
    line-height: 50px;
}

h3 {
    font-size: 20px;
    line-height: 37.3px;
}
</style>