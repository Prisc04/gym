<template>

  <div>

    <div class=" bg-blue-300 text-center font-bold w-full px-2 py-6">
          <h1 class="text-base">Choisissez une salle de sport locale et obtenez votre laissez-passer gratuit. Voir? Nous facilitons déjà la santé.</h1>
    </div>

        <div class="flex flex-col gap-4 ">
            <div class="p-4 bg-violet-900 w-1/3 text-right">
              <div class="bg-white p-4  pt-4 flex flex-row justify-between rounded-full w-full">
                  <input type=" text" placeholder="Recherche par ville et quartier" class="w-full focus:outline-none placeholder-gray-400 text-gray-800">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 text-gray-400">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"/>
                  </svg>
              </div>

              <div class="text-white pt-4 pb-4 text-sm justify-center">
                <h1 class="text-left  flex flex-row">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" />
                  </svg>
                  Nous avons trouvé ces emplacements près de chez vous (2 résultats)
                </h1>
              </div>

              <div class="flex flex-col overflow-y-auto h-[60vh] gap-4 pr-4">

                <div class="bg-white hover:border-red-400 hover:border-2 cursor-pointer shadow-lg  px-2 pt-4 justify-center">
                  <div class="flex flex-col justify-between px-2 pt-4">
                    <h1 class=" text-black text-left font-bold text-sm">
                      Fiteness Gym
                    </h1>
                    <h1 class=" text-black  text-sm">
                      11 Kilomètre
                    </h1>
                  </div>

                  <div class="flex flex-col  justify-center px-2 pt-4">
                    <h1 class=" text-black text-left text-sm p-2">
                      41 Boulevard Mohamed Zerktouni
                      Zerktouni, Casablanca-Settat 20250
                      +212(0)522274124
                    </h1>
                    <hr class="bg-gray-900 w-full border rounded-lg mb-2">
                  </div>

                  <div class="flex flex-col justify-end pb-4 font-bold text-sm">
                    <h1 @click="$router.push('/')" class="text-black bg-white  px-4 text-right  cursor-pointer hover:text-red-600">
                        ESSAI GRATUIT DE 1 JOURS
                    </h1>
                  </div>
                </div>


                <div class="bg-white hover:border-red-400 hover:border-2 cursor-pointer shadow-lg  px-2 pt-4 justify-center">

                <div class="flex flex-col justify-between px-2 pt-4">
                  <h1 class=" text-black text-left font-bold text-sm">
                    Fiteness Gym
                  </h1>
                  <h1 class=" text-black  text-sm">
                    11 Kilomètre
                  </h1>
                </div>

                <div class="flex flex-col  justify-center px-2 pt-4">
                  <h1 class=" text-black text-left text-sm p-2">
                    41 Boulevard Mohamed Zerktouni
                    Zerktouni, Casablanca-Settat 20250
                    +212(0)522274124
                  </h1>
                  <hr class="bg-gray-900 w-full border rounded-lg mb-2">
                </div>

                <div class="flex flex-col justify-end pb-4 font-bold text-sm">
                  <h1 @click="$router.push('/')" class="text-black bg-white  px-4 text-right  cursor-pointer hover:text-red-600">
                      ESSAI GRATUIT DE 1 JOURS
                  </h1>
                </div>
                </div>

                <div class="bg-white hover:border-red-400 hover:border-2 cursor-pointer shadow-lg  px-2 pt-4 justify-center">

                <div class="flex flex-col justify-between px-2 pt-4">
                  <h1 class=" text-black text-left font-bold text-sm">
                    Fiteness Gym
                  </h1>
                  <h1 class=" text-black  text-sm">
                    11 Kilomètre
                  </h1>
                </div>

                <div class="flex flex-col  justify-center px-2 pt-4">
                  <h1 class=" text-black text-left text-sm p-2">
                    41 Boulevard Mohamed Zerktouni
                    Zerktouni, Casablanca-Settat 20250
                    +212(0)522274124
                  </h1>
                  <hr class="bg-gray-900 w-full border rounded-lg mb-2">
                </div>

                <div class="flex flex-col justify-end pb-4 font-bold text-sm">
                  <h1 @click="$router.push('/')" class="text-black bg-white  px-4 text-right  cursor-pointer hover:text-red-600">
                      ESSAI GRATUIT DE 1 JOURS
                  </h1>
                </div>
                </div>

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
