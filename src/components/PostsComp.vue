<template>
    <div class="w-[550px] m-10 mx-48 drop-shadow-2xl rounded-xl bg-white border-2 box-content">
        <div class="flex items-center relative justify-start" id="head">
            <img
                class="rounded-full w-12 h-12 m-4"
                src="src/assets/mini_PP.png"
                alt=""
            />
            <span>
                <p class="font-semibold">b.a.t.u.h.a.n</p>
                <p>sincan/ankara</p>
            </span>
            <span
                class="
                    absolute
                    font-extrabold
                    text-center
                    rotate-90
                    hover:cursor-pointer
                    select-none
                    text-4xl
                    right-0
                "
                >...</span
            >
        </div>
        <div
            class="
                bg-gray-300
                flex
                justify-center
                items-center
                m-auto
                w-[550px]
                h-[550px]
            "
            id="content"
        >
            <img src="src/assets/logo.png" alt="" />
        </div>
        <div class="flex justify-between" id="buttons">
            <span class="flex my-2 ml-5">
                <img
                    class="w-7 mx-2 h-7 "
                    src="src/assets/logos/png/006-heart.png"
                    alt=""
                />
                <img
                    class="w-7 mx-2 h-7"
                    src="src/assets/logos/png/010-chatCont.png"
                    alt=""
                />
                <img
                    class="w-7 mx-2 h-7"
                    src="src/assets/logos/png/005-send.png"
                    alt=""
                />
            </span>
            <span class="flex my-2 mr-5">
                <img
                    class="w-7 h-7"
                    src="src/assets/logos/png/004-save-instagram.png"
                    alt=""
                />
            </span>
        </div>
        <div class="mx-7 " id="infos">
            <p>12.123 likes</p>
            <span class="flex">
                <p class="mr-2 font-semibold ">b.a.t.u.h.a.n</p>
                <p>açıklama vue logosu <a class="hastag" href="#">#vue</a></p>
                </span>
            <p class="text-sm opacity-80">Yorumları gör...</p>
            <p class="text-xs opacity-60">2 saat önce</p>
            <br>
        </div>
    </div>
</template>
