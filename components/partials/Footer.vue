<template>
    <footer class=" w-full  md:absolute bottom-0 md:px-4  md:py-10">
        <div class=" w-full max-w-[82rem] p-8 mx-auto md:rounded-[1.8125rem] bg-white  md:h-[17rem]">
            <div class=" w-full h-full flex md:flex-row flex-col space-y-10 md:space-y-0 items-start md:justify-between max-w-[955px]">
                <div class=" w-full max-w-[18rem] h-full flex flex-col items-start justify-between">
                   <div>
                     <img src="/images/logofooter.svg" alt="">
                   </div>
                    <p class=" text-[0.5rem] font-roboto text-black leading-[150%] font-normal hidden md:block">
                        Funtech ltd 2023 All right are reserved.
                        <br> <br>
                        Registered in UK under company number 11721421 
                        <br> <br>
                        Registered office located 17 Carlisle Street, W1D 3BU, London, England.
                    </p>
                </div>
                <div class=" flex h-full flex-col items-start space-y-4">
                    <h1 class=" text-[#12026B] font-ubuntu font-bold text-[1.125rem]">Product</h1>
                     <nuxt-link to="/">
                        <span class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">DEGA</span>
                    </nuxt-link>
                      <nuxt-link to="/">
                        <span class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">Coingames</span>
                    </nuxt-link>
                      <nuxt-link to="/">
                        <span class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">NewGames <br class=" hidden md:block"> format</span>
                    </nuxt-link>
                </div>
                 <div class=" flex h-full flex-col items-start space-y-4">
                    <h1 class=" text-[#12026B] font-ubuntu font-bold text-[1.125rem]">Company</h1>
                     <nuxt-link to="/">
                        <span class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">About</span>
                    </nuxt-link>
                      <div class=" relative">
                            <nuxt-link to="/" class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">
                                Careers
                            </nuxt-link>
                            <img src="/images/wearehiring.svg" class=" absolute top-5 lg:top-0 w-full h-full lg:-right-16" alt="">
                        </div>
                      <nuxt-link to="/contact-us">
                        <span class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">Contact us</span>
                    </nuxt-link>
                      <nuxt-link to="/">
                        <span class=" text-[#12026B] font-ubuntu font-light text-[1.125rem]">News</span>
                    </nuxt-link>
                </div>
                 <div class=" flex h-full flex-col items-start space-y-4 w-full border-t border-black pt-5 md:pt-0 md:border-none md:w-fit">
                    <h1 class=" text-[#12026B] font-ubuntu font-bold text-[1.125rem]">Socials</h1>
                     <nuxt-link to="/">
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                        <path d="M17.1761 4.24268H19.9362L13.9061 11.0201L21 20.2427H15.4456L11.0951 14.6493L6.11723 20.2427H3.35544L9.80517 12.9935L3 4.24268H8.69545L12.6279 9.3553L17.1761 4.24268ZM16.2073 18.6181H17.7368L7.86441 5.78196H6.2232L16.2073 18.6181Z" fill="black"/>
                      </svg>
                    </nuxt-link>
                      <nuxt-link to="/">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
                          <path fill-rule="evenodd" clip-rule="evenodd" d="M4.5 3.24268C3.67157 3.24268 3 3.91425 3 4.74268V19.7427C3 20.5711 3.67157 21.2427 4.5 21.2427H19.5C20.3284 21.2427 21 20.5711 21 19.7427V4.74268C21 3.91425 20.3284 3.24268 19.5 3.24268H4.5ZM8.52076 7.2454C8.52639 8.20165 7.81061 8.79087 6.96123 8.78665C6.16107 8.78243 5.46357 8.1454 5.46779 7.24681C5.47201 6.40165 6.13998 5.72243 7.00764 5.74212C7.88795 5.76181 8.52639 6.40728 8.52076 7.2454ZM12.2797 10.0044H9.75971H9.7583V18.5643H12.4217V18.3646C12.4217 17.9847 12.4214 17.6047 12.4211 17.2246C12.4203 16.2108 12.4194 15.1959 12.4246 14.1824C12.426 13.9363 12.4372 13.6804 12.5005 13.4455C12.7381 12.568 13.5271 12.0013 14.4074 12.1406C14.9727 12.2291 15.3467 12.5568 15.5042 13.0898C15.6013 13.423 15.6449 13.7816 15.6491 14.129C15.6605 15.1766 15.6589 16.2242 15.6573 17.2719C15.6567 17.6417 15.6561 18.0117 15.6561 18.3815V18.5629H18.328V18.3576C18.328 17.9056 18.3278 17.4537 18.3275 17.0018C18.327 15.8723 18.3264 14.7428 18.3294 13.6129C18.3308 13.1024 18.276 12.599 18.1508 12.1054C17.9638 11.3713 17.5771 10.7638 16.9485 10.3251C16.5027 10.0129 16.0133 9.81178 15.4663 9.78928C15.404 9.78669 15.3412 9.7833 15.2781 9.77989C14.9984 9.76477 14.7141 9.74941 14.4467 9.80334C13.6817 9.95662 13.0096 10.3068 12.5019 10.9241C12.4429 10.9949 12.3852 11.0668 12.2991 11.1741L12.2797 11.1984V10.0044ZM5.68164 18.5671H8.33242V10.01H5.68164V18.5671Z" fill="black"/>
                        </svg>
                    </nuxt-link>
                   
                </div>
            </div>

            <p class=" text-black font-roboto text-[0.875rem] font-normal pt-4 md:pt-0 md:float-right lg:-mt-5 ">
                © 2023 Funtech. All rights reserved.
            </p>
        </div>
    </footer>
</template>