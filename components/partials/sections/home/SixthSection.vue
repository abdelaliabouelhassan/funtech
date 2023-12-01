<template>
    <section class=" w-full flex flex-col items-start space-y-4 pt-10 overflow-hidden">
      <div class=" w-full flex p-4 max-w-[1305px] mx-auto">
         <div class=" relative w-full m-auto max-w-[21.56481rem] md:max-w-full">
            
        <div class=" box-shadow absolute top-0 left-0 md:w-[32.75rem] md:h-[5.6875rem] h-[3.6875rem] w-[21.56481rem]"></div>
         <button class=" h-[3.6875rem] md:h-[5.6875rem] hover:scale-110 duration-200 bg-white z-10 relative max-w-[21.56481rem] md:max-w-[32.75rem] w-full rounded-[0.625rem] flex justify-center items-center space-x-4">
            <span class=" text-black text-[1.21569rem] md:text-[1.875rem] font-ubuntu text-center font-light">Our technology & their benefits </span>
            <img src="/images/home/Trophy.svg" class=" w-full  md:max-w-[2.4375rem] max-w-[1.58038rem] h-[1.58038rem] md:h-[2.4375rem]" alt="">
        </button>
       </div>
      </div>

      <div class=" w-full grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4 px-4 py-10 max-w-[1305px] mx-auto">
            <div  class="flip-container w-full  max-w-[29.0625rem] h-[30rem] sm:h-[43.4375rem]">
                <div   class="flip-card w-full h-full">
                    <div class="front face relative rounded-[0.625rem] overflow-hidden">
                        <img src="/images/home/GenerativeExpand.png" class=" w-full h-full" alt="">
                        <div class="  absolute top-0 left-0 p-4">
                            <p class=" text-white font-ubuntu text-[2.15rem] lg:text-[3.125rem] font-bold leading-[150%]">
                                Better <br> Security <br>
                            <span class=" font-light">  harder to attack your network</span>
                            </p>
                        </div>
                    </div>
                    <div class="back face bg-[#0F0E13] w-full h-full p-4 rounded-[0.625rem]">
                        <p class=" text-white font-ubuntu text-[2.15rem] lg:text-[3.125rem] font-bold  leading-[150%]">
                            Better <br> Security <br> <br>
                        </p>
                        <span class=" text-[1.25rem] font-normal leading-[150%] text-white font-ubuntu">A decentralized network makes it more difficult for malicious entities to attack the network and attempt to control it.</span>
                    </div>
                </div>
            </div>
            <div  class="flip-container w-full  max-w-[29.0625rem] h-[30rem] sm:h-[43.4375rem]">
                <div   class="flip-card w-full h-full">
                    <div class="front face relative rounded-[0.625rem] overflow-hidden">
                        <img src="/images/home/arrowcard.png" class=" w-full h-full " alt="">
                        <div class="  absolute top-0 left-0 p-4">
                            <p class=" text-white font-ubuntu text-[2.15rem] lg:text-[3.125rem] font-bold leading-[150%]">
                            Instant <br> transactions <br>

                            <span class=" font-light">with our Layer 2 technology</span>
                            </p>
                        </div>
                    </div>
                    <div class="back face bg-[#0B1021] w-full h-full p-4 rounded-[0.625rem]">
                        <p class=" text-white font-ubuntu text-[2.15rem] lg:text-[3.125rem] font-bold  leading-[150%]">
                            Instant <br> transactions <br> <br>
                        </p>
                         


                        <p class=" text-[1.25rem] font-normal leading-[150%] text-white font-ubuntu">
                            Second-layer solutions enable near instantaneous transactions, as there is less dependence on intermediaries. 
                            <br> <br>
                            We lead in the innovation of global digital payments, making them fast, secure and accessible to all.
                        </p>
                    </div>
                </div>
            </div>
            <div  class="flip-container w-full  max-w-[29.0625rem] h-[30rem] sm:h-[43.4375rem]">
                <div   class="flip-card w-full h-full">
                    <div class="front face relative rounded-[0.625rem] overflow-hidden">
                        <img src="/images/home/techcard.png" class=" w-full h-full " alt="">
                        <div class="  absolute top-0 left-0 p-4">
                            <p class=" text-[#100146] font-ubuntu text-[2.15rem] lg:text-[3.125rem] font-bold leading-[150%]">
                                Efficiency & <br> Accessibility <br>
                               <span class=" font-light"> Less <br> computational <br> load.</span>
                             

                            </p>
                        </div>
                    </div>
                    <div class="back face bg-[#F6F5F5] w-full h-full p-4 rounded-[0.625rem]">
                        <p class=" text-[#100146] font-ubuntu text-[2.15rem] lg:text-[3.125rem] font-bold  leading-[150%]">
                            Efficiency &  <br> Accessibility <br> <br>
                        </p>
                        <p class=" text-[1.25rem] font-normal leading-[150%] text-[#100146] font-ubuntu">
                            Decentralization reduces the computational load on the main chain.
                            <br> <br>
                            leading to more efficient overall resource utilization 
                             <br> <br>
                            this allows users to engage without stringent compliance requirements.
                        </p>
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
    flex-shrink: 0;
 }


.flip-container {
    position: relative;
    margin: 10px auto;
    width: 100%;
    z-index: 1;
}
.face.back {
    display: none;
}
.flip-container {
    -webkit-perspective: 850;
    -moz-perspective: 850px;
}
.flip-card {
    width: 100%;
    height: 100%;
    -webkit-transform-style: preserve-3d;
    -webkit-transition: -webkit-transform 1s;
    -moz-transform-style: preserve-3d;
    -moz-transition: -moz-transform 1s;
}
.flip-container:hover .flip-card {
    -webkit-transform: rotateY(180deg);
    -moz-transform: rotateY(180deg);
}
.face {
    position: absolute;
    width: 100%;
    height: 100%;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
}
.face.back {
    display: block;
    -webkit-transform: rotateY(180deg);
    -webkit-box-sizing: border-box;
    -moz-transform: rotateY(180deg);
    -moz-box-sizing: border-box;
}
</style>