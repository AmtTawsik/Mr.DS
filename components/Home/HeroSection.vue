<template>
    <div class="grid grid-cols-12 items-center">
        <div class="col-span-12 md:col-span-6 w-11/12 mx-auto md:hidden mb-5">
            <img :src="hero1" alt="">
        </div>
        <div class="col-span-12 md:col-span-6 bg-[#F8F8FF] h-full flex">
            <div class="w-10/12 mx-auto my-auto">
                <h2 class="text-3xl md:text-6xl font-semibold md:w-8/12">Contracts Made Digital</h2>
                <p class="text-xl text-gray-600 md:w-7/12 my-5">Create, sign and store all your contracts in one, safe
                    place.</p>
                <form class="my-5">
                    <div class="flex">
                        <div class="relative w-full md:w-10/12">
                            <input type="search" id="search-dropdown"
                                class="block px-2.5 py-5 w-full z-20 text-sm text-gray-900 bg-white border-l-2 border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-l-gray-700  dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:border-blue-500"
                                placeholder="Your Email Address" required>
                            <button type="submit"
                                class="absolute top-0 right-0 py-2.5 px-5 text-sm font-medium h-full text-white bg-blue-700 border border-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                <span class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" fill="none"
                                        viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                        <path stroke-linecap="round" stroke-linejoin="round"
                                            d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m0 12.75h7.5m-7.5 3H12M10.5 2.25H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
                                    </svg>
                                    Get Started</span>
                            </button>
                        </div>
                    </div>
                </form>
                <p>Or <span class="text-blue-600 ml-1 hover:border-b cursor-pointer hover:border-blue-600 ">Book a Demo</span></p>
            </div>

        </div>
        <div class="col-span-12 md:col-span-6 w-11/12 mx-auto hidden md:flex">
            <img :src="hero1" alt="">
        </div>
    </div>
</template>

<script setup>
import hero1 from '../../assets/images/hero1.jpg'
</script>