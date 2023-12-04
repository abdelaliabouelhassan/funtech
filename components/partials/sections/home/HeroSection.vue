<template>
    <section class=" w-full hero pt-28 px-4 pb-10 space-y-10 lg:space-y-28 relative">
            <div class=" w-full flex flex-col items-center  max-w-[65.875rem] mx-auto space-y-8">
                <h1 class=" font-ubuntu text-[3.125rem] md:text-[5rem] lg:text-[6.25rem] font-bold text-center leading-[100%] text-[#100146]">We Develop Blockchain Solutions</h1>
                <p class=" text-black font-ubuntu text-center text-[1.25rem] sm:text-[1.875rem] font-light leading-[150%]">
                    We lead the innovation on global digital payment by bringing it into the Web3
                </p>
                <div class=" w-full relative justify-center flex pt-4"> 
                    <div class="btn-blur absolute"></div>
                   
                    <nuxt-link to="/contact-us"  class="btn btn-shadow-1 relative z-10" >
                            <button class="btn">Contact us</button>
                    </nuxt-link>
                </div>
                
            </div>

            <div class=" w-full max-w-[65.58569rem] lg:h-[30rem] mx-auto">
            <div class=" lg:absolute w-full h-full max-w-[65.58569rem] max-h-[45.31675rem] z-20 md:-bottom-[10.5rem]">
                <img src="/images/home/hero.png" class=" w-full h-full object-cover" alt="">
            </div>
            </div>
           
    </section>
</template>


<style scoped>
 .hero {
    background: linear-gradient(180deg, #F6F2FF 0%, #100146 100%);
 }
</style>