<template>
    <div class="bg-[#181B3F] mt-24">
        <h2 class="title text-center font-extrabold w-[35%] mr-auto ml-auto pt-16 text-white">MyDigitalSchool, c'est aussi un blog avec des conseils</h2>
        <div class="flex justify-around w-[70%] mr-auto ml-auto mt-28 pb-32">
            <CardBlog v-for="content in contents" :key="content.date" :title="content.title" :date="content.date" :images="content.images" />
        </div>
    </div>
</template>
<script setup lang="ts">
import CardBlog from '../Utils/CardBlog.vue';
import rectangle1 from '@/assets/images/blog/Rectangle1.jpg'
import rectangle2 from '@/assets/images/blog/Rectangle2.jpg'
import rectangle3 from '@/assets/images/blog/Rectangle3.svg'

const contents = [
{
    title: 'Commment devenir développeur web',
    date: 'Posté le 4 mars',
    images: rectangle1,
},
{
    title: 'UX vs UI Design, quelle est la différence ?',
    date: 'Posté le 5 avril',
    images: rectangle2,
},
{
    title: 'Top 10 des métiers du digital en 2023',
    date: 'Posté le 9 avril',
    images: rectangle3,
},
{
    title: 'Commment devenir développeur web',
    date: 'Posté le 4 mars',
    images: rectangle1,
},
]

</script>

<style scoped>
h2 {
    font-size: 41.4px;
    line-height: 50px;
}
</style>