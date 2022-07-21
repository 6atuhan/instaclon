<template>
    <div class="relative z-0 w-[550px]">
        <div class="absolute w-[550px] h-10 mx-48 my-10 ">
            <img @click="goForward" class="select-none cursor-pointer absolute rotate-90 h-6 bg-slate-50 rounded-2xl p-1 opacity-50 hover:opacity-100 hover:drop-shadow-lg transition-all right-2" src="src/assets/logos/png/007-go-up.png" alt="">
        <img @click="goBack" class="select-none cursor-pointer absolute -rotate-90 h-6 bg-slate-50 rounded-2xl p-1 opacity-50 hover:opacity-100 hover:drop-shadow-lg transition-all left-2" src="src/assets/logos/png/007-go-up.png" alt="">
        </div>
        <div id="stories" class="w-[550px] h-32 mx-48 my-10 bg-white border-2 rounded-xl px-5 flex  items-center overflow-hidden transition-all">
            <div v-for="i in 10" :key="i" class="flex flex-col justify-center items-center text-center"><div class="story-circle rot-content flex-shrink-0 bg-lime-300"> </div> <p>batuhan</p></div>
            
        </div>
    </div>
</template>

<script setup>

const goForward =()=>{
    document.getElementById('stories').scrollLeft +=100;
}
const goBack =()=>{
    document.getElementById('stories').scrollLeft -=100;
}

</script>

<style>

*{
    scroll-behavior: smooth;
}

</style>