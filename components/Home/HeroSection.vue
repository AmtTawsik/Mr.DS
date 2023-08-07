<template>
    <div class="grid grid-cols-12 items-center">
        <div class="col-span-12 md:col-span-6 mx-auto md:hidden w-full">
            <img :src="hero1" alt="">
        </div>
        <div class="col-span-12 md:col-span-6 py-5 md:py-0 bg-gradient-to-r from-[#061E38] to-[#061e38] h-full flex">
            <div class="w-10/12 mx-auto my-auto text-white">
                <h2 class="text-3xl md:text-6xl font-semibold md:w-10/12">Developing your ideas into <span
                        class="text-[#1db0f4]">reality=</span></h2>
                <p class="text-xl text-gray-200 md:w-7/12 my-5 md:my-8">We provide custom software solutions for any industry. Creating high-value software and technology for your business.</p>
                <div>
                    <button class="bg-[#00B2FF] hover:bg-[#269bcd] border border-[#00B2FF] px-5 py-2.5 text-lg rounded-lg font-semibold mr-5">Get in touch</button>
                    <button class="bg-none border border-white hover:border-[#269bcd] hover:text-[#269bcd] px-5 py-2.5 text-lg rounded-lg font-semibold">See the work</button>
                </div>
            </div>
        </div>
        <div class="col-span-12 md:col-span-6 hidden md:flex relative">
            <!-- Image -->
            <img class="w-full" :src="hero1" alt="">

            <!-- Gradient overlay -->
            <div class="absolute inset-0 bg-gradient-to-r from-[#061e38] to-transparent w-11/12"></div>
        </div>
    </div>
</template>

<script setup>
import hero1 from '../../assets/images/hero1.jpeg'
</script>