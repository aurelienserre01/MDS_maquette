<template>
    <div class="pt-16 mb-44">
        <div class="header-alumnis flex w-[70%] mb-24 justify-between mr-auto ml-auto">
            <div>
                <h2 class="title w-[60%] font-extrabold">Qu’est-ce que nos alumnis en pensent ?</h2>
            </div>
            <div class="flex items-center">
                <div class=" button-fleche border-[1px] border-[#29B7C5] rounded-full p-4 h-14 mr-4">
                    <img :src="flechGauche" alt="">
                </div>
                <div class="button-fleche bg-[#29B7C5] rounded-full p-4 h-14">
                    <img :src="flechDroite" alt="">
                </div>
            </div>
        </div>
        <div class="post-alumni flex w-[70%] justify-between mr-auto ml-auto">
            <div class="card rounded-[20px] w-[560px] h-[276px] bg-white p-8">
                <div class="card-header flex items-center">
                    <img width="52" height="52" class="photo-profile" :src="Rectangle13" alt="">
                    <div class="description ml-3">
                        <div class="prenom font-semibold">
                            Mélanie
                        </div>
                        <div class="annee font-normal text-gray-400">
                            Étudiante en 2015
                        </div>
                    </div>
                </div>
                <div class="content mt-8 w-[90%] text-[#181B3F]">
                    J’ai passé clairement mes 2 meilleurs années scolaires à MyDigitalSchool. L’ambiance, les intervenants
                    et les locaux m’ont permis de m’épanouir, gros big up pour la connexion internet ! ❤️
                </div>
                <div class="date-post absolute bottom-8 font-bold">
                    Mars 2022
                </div>
            </div>
            <div class="card rounded-[20px] w-[560px] h-[276px] bg-white p-8">
                <div class="card-header flex items-center">
                    <img width="52" height="52" class="photo-profile" :src="Rectangle14" alt="">
                    <div class="description ml-3">
                        <div class="prenom font-semibold">
                            Léo
                        </div>
                        <div class="annee font-normal text-gray-400">
                            Étudiant en 2015
                        </div>
                    </div>
                </div>
                <div class="content mt-8 w-[90%] text-[#181B3F]">
                    J’ai passé clairement mes 2 meilleurs années scolaires à MyDigitalSchool. L’ambiance, les intervenants
                    et les locaux m’ont permis de m’épanouir, gros big up pour la connexion internet ! ❤️
                </div>
                <div class="date-post absolute bottom-8 font-bold">
                    Juin 2017
                </div>
            </div>
        </div>
        
    </div>
    
</template>
<script setup lang="ts">
import Rectangle13 from '@/assets/images/profiles/Rectangle13.jpg'
import Rectangle14 from '@/assets/images/profiles/Rectangle14.jpg'
import flechGauche from '@/assets/images/icons/FlecheGauche.svg'
import flechDroite from '@/assets/images/icons/FlecheDroite.svg'

</script>
<style scoped>

#losange {
  width  : 0;
  height : 0;
  border : 25px solid transparent;
  border-bottom : 35px solid green;
  position : relative;
  top : -25px;
}
#losange:after {
  width  : 0;
  height : 0;
  content : '';
  position : absolute;
  left : -50px;
  top  : 35px;
  border : 25px solid transparent;
  border-top : 35px solid green;
}

h2 {
    font-size: 41.4px;
    line-height: 50px;
}

.prenom .content .date-post {
    font-size: 15px;
    line-height: 20px;
}

.button-fleche {
    box-sizing: border-box;
}

.card {
    box-shadow: 0px 0px 30px rgba(0, 0, 0, 0.1);
}</style>