<template>
    <div style="z-index: 999;" class="sticky top-0">
        <div class="bg-indigo-900 text-gray-100 items-center py-4 px-3.5 flex flex-row  justify-between text-center font-extrabold  w-full">

            <div class="text-lg">
            <img src="https://st4.depositphotos.com/18426998/20265/i/450/depositphotos_202652228-stock-photo-gymnasium-fitness-logo-in-vector.jpg" alt="" width="50" height="T00" title="AC Gym" class="ml-4 ml-md-0">
            </div>

            <div class="text-lg flex flex-row">
            <ul class="flex lg:flex-row flex-row mt-4 text-base text-gray-500 gap-8 justify-center"
                style="list-style-type: none">
                <li class="hover:opacity-75 text-white cursor-pointer" @click="$router.push('/')">
                    SALLE DE GYM
                </li>
                <li class="hover:opacity-75 text-white cursor-pointer" @click="$router.push('/about')">ENTRAINEMENT</li>
                <li class="hover:opacity-75 text-white cursor-pointer"  @click="$router.push('/detail')">POURQUOI ADHÉRER</li>
                <li  class="hover:opacity-75 text-white cursor-pointer"  @click="$router.push('/')">CONTACT</li>
                <li class="hover:opacity-75 text-white cursor-pointer"  @click="$router.push('/')">EMPLACEMENTS</li>
            </ul>
            </div>

            <div class="text-lg">
            <button class="bg-blue-800 text-white px-6 py-2 rounded-full">
                Essayez-nous gratuitement
            </button>
            </div>

        </div>
    </div>
</template>
