<template>
    <div>
        <div class="flex justify-center items-center mt-8 md:mt-16 mb-5">
            <img class="w-10" :src="about" alt="">
            <p class="text-2xl font-bold">About Us</p>
        </div>
        <div class="bg-gradient-to-t from-[#F1F8FF] to-[#f7fbff] w-full overflow-hidden relative">
            <div class="w-11/12 mx-auto">
                <h3 class="text-2xl font-bold md:text-4xl text-center py-8">We will help you with our creative thinking</h3>
                <div class="flex justify-center">
                    <img class="rounded-xl" :src="devlopment" alt="">
                </div>
                <div class="my-10 text-center md:w-6/12">
                    <dl class="grid gap-8 text-gray-900 sm:grid-cols-3 dark:text-white">
                        <div class="flex flex-col items-center justify-center">
                            <dt class="mb-2 text-3xl md:text-4xl font-extrabold">12<span class="text-blue-600">+</span></dt>
                            <dd class="font-bold text-gray-500 dark:text-gray-400">Years of Operation</dd>
                        </div>
                        <div class="flex flex-col items-center justify-center">
                            <dt class="mb-2 text-3xl md:text-4xl font-extrabold">50<span class="text-blue-600">+</span>
                            </dt>
                            <dd class="font-bold text-gray-500 dark:text-gray-400">Project Delivered</dd>
                        </div>
                        <div class="flex flex-col items-center justify-center">
                            <dt class="mb-2 text-3xl md:text-4xl font-extrabold">250<span class="text-blue-600">+</span></dt>
                            <dd class="font-bold text-gray-500 dark:text-gray-400">Happy Clients</dd>
                        </div>
                    </dl>
                </div>
                <div class="p-5 md:p-8 bg-white rounded-xl md:w-4/12 md:absolute bottom-8 right-44">
                    <h5 class="text-[#1BB1FF] cursor-pointer">Our mission ></h5>
                    <p>Mr. Dynamic Solutions combines high quality software development with excellent service to add value to your business. Our commitment is to deliver results and save you time and money, while developing a long-term relationship that benefits us both</p>
                </div>
            </div>
        </div>
        <svg class="w-full" width="500" height="80" viewBox="0 0 500 80" preserveAspectRatio="none">
            <path d="M0,0 L0,40 Q250,80 500,40 L500,0 Z" fill="#F1F8FF" />
        </svg>


    </div>
</template>

<script setup>
import about from '../../assets/images/logos/about.jpeg'
import devlopment from '../../assets/images/devlopment.jpg'
</script>