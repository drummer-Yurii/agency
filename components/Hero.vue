<template>
    <section class="lg:mx-desktop bg-[#f3f7f5] rounded-3xl mt-4 relative">
        <!-- Stat Card -->
        <div 
            class="absolute rounded-2xl p-4 bg-white bottom-4 left-[40%] z-40 hover:scale-105 hover:shadow-lg shadow shadow-black/5 transition-all duration-300"
        >
            <img src="/stat.png" alt="Investor Status" class="mx-auto" />
            <p>80% startups</p>
            <h1 class="text-lg font-extrabold">Investors</h1>
        </div>
        <div class="absolute right-[10%] top-1/2 rounded-full w-5 h-5 bg-green-900">

        </div>
        <div class="absolute left-[40%] bottom-7 rounded-full w-5 h-5 bg-yellow-500">

        </div>
        <div class="flex">
            <div class="basis-1/2 pl-20 pt-24 relative">
                <h1 
                class="font-bold text-6xl leading-[1.15] relative z-40 animate-slideDown"
                >
                <div class="absolute right-[20%] top-0 rounded-full w-5 h-5 bg-green-500/50">
        
                </div>
                    Join the world's <br />
                    largest startup <br />
                    community
                </h1>
                <p class="mt-3 text-gray-600 font-medium text-xl">
                    Experience the startup ecosystem _ invest in startups
                </p>
                <p class="mt-3 text-gray-600 font-medium text-xl">
                    Research the fastest growing companies.
                </p>
                <div class="mt-16">
                    <NuxtLink 
                        to="#"
                        class="border border-transparent hover:border-[#3e3e3e] py-5 px-10 rounded-full font-medium hover:bg-[#3e3e3e] bg-black text-white transition-all"
                    >
                        Get Started
                    </NuxtLink>
                </div>
            </div>
            <div class="basis-1/2 overflow-hidden relative hidden lg:block">
                <!-- Chat Button -->
                <div class="absolute top-5 right-[15%] group cursor-pointer">
                    <div class="h-20 w-16 bg-amber-400 rounded-full relative">
                        <img 
                            src="/arrow.png" alt="Arrow Icon"
                            class="w-full absolute -left-8 top-3 group-hover:translate-x-4 transition-all duration-300" 
                        />
                    </div>
                    <p class="font-bold text-xl">Let's chat <br />with us!</p>
                </div>
                <!-- Customer review -->
                <div class="absolute top-1/2 right-[10%]">
                    <div class="flex relative p-2 rounded-full bg-white w-80 cursor-pointer hover:scale-105 transition-all duration-300">
                        <!-- Heart -->
                        <div class="right-5 -top-5 p-2 h-11 w-11 bg-gradient-to-br from-red-100 via-red-500 to-red-600 rounded-full shadow-lg shadow-red-500">
                            <img src="/heart.png" alt="Heart Icon">
                        </div>
                        <img 
                            src="https://randomuser.me/api/portraits/men/75.jpg" 
                            alt="Random Customer" 
                            class="w-14 h-14 rounded-full" 
                        />
                        <p class="text-lg font-medium text-gray-600 mx-4">
                            <span class="font-bold text-black">Mikey</span> has liked
                            <br />
                            this community
                        </p>
                    </div>
                </div>
                <img src="/home.png" alt="Image of a woman" class="object-cover h-[100$]" />
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style>

</style>