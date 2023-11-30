<template>
    <section class=" w-full flex flex-col items-start space-y-4 pt-10 overflow-hidden">
      <div class=" w-full p-4 max-w-[1305px] mx-auto">
         <div class=" relative w-full">
        <div class=" box-shadow absolute top-0 left-0"></div>
         <button class=" h-[5.6875rem] hover:scale-110 duration-200 bg-white z-10 relative max-w-[17.6875rem] w-full rounded-[0.625rem] flex justify-center items-center space-x-4">
            <span class=" text-black text-[1.875rem] font-ubuntu text-center font-light">Our Solutions </span>
            <img src="/images/home/OpenBox.svg" class=" w-full h-full max-w-[2.4375rem] max-h-[2.4375rem]" alt="">
        </button>
       </div>
      </div>

      <div class=" w-full bg-[#005EFF] px-4 py-10">
        <div class=" w-full flex md:items-center md:flex-row flex-col items-start md:space-y-0 space-y-10 md:justify-between md:space-x-10 max-w-[1305px] mx-auto">
            <div class=" w-full md:max-w-[31.125rem] flex flex-col items-start space-y-10">
                 <img src="/images/home/logo.svg" alt="">
                 <h1 class=" text-[2.5rem] md:text-[3.125rem] text-white font-bold leading-[150%] font-proximanova">The Future of Digital Payment</h1>
                 <p class=" text-white text-xl font-normal font-proximanova leading-[150%]">
                    By <span class=" font-medium">enabling a </span> fully decentralized ecosystem, our de.ga technology gives users access to a trustless system with rapidly processed transactions and reduced fees
                    <br> <br>
                    The technology works as a second-layer framework on Binance, Ethereum and Polygon, enabling faster payments directly through non-custodial wallets.
                 </p>
            </div>

         <div class=" w-full flex justify-end md:w-fit">
               <div class=" w-full relative max-w-[29.6875rem]">
                <img src="/images/home/mockuuups-iphone.png" class=" w-full h-full object-cover ml-[2rem]" alt="">
                <div class=" absolute top-10 -left-14 md:-left-14 ">
                    <img src="/images/home/asset1.png" alt="">
                </div>
                <div class=" absolute -bottom-5 md:bottom-5 lg:bottom-10 left-auto right-4 md:right-auto md:-left-16 ">
                     <img src="/images/home/coins.png" alt="">
                </div>
            </div>
         </div>
        </div>
      </div>
    </section>
</template>


<style scoped>
 .box-shadow {
    border-radius: 0.625rem;
    background: #100146;
    filter: blur(10px);
    width: 17.6875rem;
    height: 5.6875rem;
    flex-shrink: 0;
 }
</style>