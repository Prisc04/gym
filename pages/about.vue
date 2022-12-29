<template>
   <div class="flex flex-col gap-6 container mx-auto   justify-between" >
        <div class="py-10 font-bold  flex flex-row justify-center">
          <h1 class="text-5xl text-center">Prestations de Coaching et <br> d’Entraînements</h1>
        </div>

        <div class=" flex flex-row justify-center">
            <h1 class="text-base text-center">Que vous soyez novice en sport ou un professionnel du fitness, nous sommes là pour vous proposer une variété d’options d’entraînements, des conseils et
                <br> un soutien convivial pour vous aider à rester sur la bonne voie et à atteindre vos objectifs. Obtenez une meilleure forme dès aujourd’hui !
            </h1>
        </div>

        <div class="flex flex-row justify-center text-lg py-10 px-8">
            <button @click="$router.push('/')" class="text-black bg-white  border-black  px-6 py-4 rounded-full  cursor-pointer hover:bg-gray-500 hover:text-white border-2">
                TROUVER VOTRE SALLE DE GYM LA PLUS PROCHE
            </button>
        </div>

        <div class="flex flex-row justify-center mx-32 gap-8 mb-32">
            <div   class="flex flex-col justify-start shadow-2xl">
                <img src="http://sites.edb.utexas.edu/uploads/sites/87/2016/08/Exercise-RX-1024x678.jpg" alt="" class="border-black w-30 h-50 ">

                <div class="flex flex-col text-base text-center px-3 pt-6  py-4 justify-center gap-4 ">
                  <h1 class="text-base text-center font-bold"> CONSULTATION FITNESS
                    </h1>
                    <h1 class="text-xs font-medium text-center ">
                        À travers un bref sondage, une conversation et une évaluation de mouvements, notre équipe vous prescrira le programme idéal pour vous aider à démarrer et vous mettre sur la bonne voie pour atteindre vos objectifs de remise en forme.
                    </h1>
                </div>
            </div>

            <div   class="flex flex-col justify-start shadow-2xl">
                <img src="http://sites.edb.utexas.edu/uploads/sites/87/2016/08/Exercise-RX-1024x678.jpg" alt="" class="border-black w-30 h-50 ">

                <div class="flex flex-col text-base text-center px-3 pt-6  py-4 justify-center gap-4 ">
                  <h1 class="text-base text-center font-bold">ENTRAÎNEMENTS <br> INDIVIDUELS
                    </h1>
                    <h1 class="text-xs font-medium text-center ">
                        Entraînements individuels personnalisés avec un coach personnel certifié, conditionné pour vous rendre plus fort de manière intrinsèque.
                    </h1>
                </div>
            </div>

            <div   class="flex flex-col justify-start shadow-2xl">
                <img src="http://sites.edb.utexas.edu/uploads/sites/87/2016/08/Exercise-RX-1024x678.jpg" alt="" class="border-black w-30 h-50 ">

                <div class="flex flex-col text-base text-center px-3 pt-6  py-4 justify-center gap-4 ">
                  <h1 class="text-base text-center font-bold"> COURS COLLECTIFS
                    </h1>
                    <h1 class="text-xs font-medium text-center ">
                        Entraînements complets du corps conçus pour accroître la force et l’endurance, tout en utilisant le dynamisme du groupe et l’expertise du coach personnel certifié afin d’optimiser vos résultats.
                    </h1>
                </div>
            </div>

        </div>

   </div>
</template>

  <script>
  export default {
    name: 'index'
  }
  </script>
