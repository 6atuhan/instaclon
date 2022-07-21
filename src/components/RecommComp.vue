<template>
    <div class="rounded-lg w-72 h-96 float-right mt-10 mr-48 top-28 z-20 hidden lg:inline-block md:hidden">

         <div class="flex items-center relative justify-between " id="head">
            <div class="flex items-center leading-none">
                <img
                class="rounded-full w-12 h-12 m-4"
                src="src/assets/mini_PP.png"
                alt=""/>
            <span>
                <p class="font-semibold  ">b.a.t.u.h.a.n</p>
                <small class="">batuhan boran</small>
            </span>
            </div>
            <a class="hastag float-right mr-4" href="#">değiştir</a>
        </div>
        <div id="suggestion" class="mt-10 px-4">
            <div class="flex justify-between items-center">
                <p class="opacity-80 font-semibold">Senin için önerilenler</p>
                <p class="font-semibold">Hepsini Gör</p>
            </div>
           <ul class>
            <li v-for="i in 3" :key="i" class=" h-14 flex items-center gap-4 justify-between"><!--user-->

                <div class="flex items-center leading-none">
                <img
                class="rounded-full w-12 h-12 m-4"
                src="src/assets/ronaldo-pp.webp"
                alt=""/>
                 <span>
                <p class="font-semibold  ">cr7</p>
                <small class="">cristiano ronaldo</small>
                </span>
                </div>
                <a class="hastag float-right mr-2" href="#">Takip Et</a>
            </li>
           
           </ul>
            
        </div>
    </div>
</template>