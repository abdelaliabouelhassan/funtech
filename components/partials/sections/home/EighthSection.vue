<template>
    <section class=" w-full pt-10 md:pt-44 pb-20 relative ">

        <div class=" absolute -left-20 top-[40rem] md:top-[10rem]">
            <img src="/images/home/dotsbg.svg" alt="">
        </div>
      
      <div class=" w-full flex flex-col items-center space-y-20 max-w-[1312px] mx-auto relative z-10 px-4">
            <div class=" flex flex-col items-center space-y-2">
                <h1 class=" text-[#12026B] text-center font-ubuntu text-[2.25rem] md:text-[3.125rem] font-bold">Meet Our Team</h1>
                <span class=" text-center text-[#12026B] font-ubuntu text-[1rem] md:text-[1.25rem] font-light">Get to know the key members of our team</span>
            </div>

            <div class=" w-full grid grid-cols-1 md:grid-cols-2 gap-x-10 gap-y-20 md:pt-28">
                <div class=" flex flex-col items-center space-y-4">
                    <div class=" w-20 h-20 rounded-full bg-gray-400 overflow-hidden">
                        <img src="/images/home/president.png" alt="">
                    </div>
                    <div class=" text-center">
                        <h1 class=" font-roboto text-black text-lg md:text-xl font-semibold leading-[150%]">Edoardo Narduzzi</h1>
                        <span class=" font-roboto text-black text-base md:text-lg font-normal leading-[150%]">President</span>
                    </div>
                    <p class=" font-roboto text-black text-base text-center max-w-[39rem] font-normal leading-[150%]">
                        Certified Public Accountant and serial entrepreneur who founded NETikos, TechEdge and Mashfrog Group. He has held senior positions at Telecom Italia and the Italian Ministry of Finance, and currently serves as president of Builg Inc and Wattyo Lda and holds several directorships in other companies
                    </p>
                    <div class=" flex items-center space-x-3">
                        <a href="" target="_blank" v-html="linkding"></a>
                        <a href=""  target="_blank" v-html="twitter"></a>
                    </div>
                </div>
                 <div class=" flex flex-col items-center space-y-4">
                    <div class=" w-20 h-20 rounded-full bg-gray-400 overflow-hidden">
                        <img src="/images/home/md.png" alt="">
                    </div>
                    <div class=" text-center">
                        <h1 class=" font-roboto text-black text-lg md:text-xl font-semibold leading-[150%]">Enrico Giancaterina</h1>
                        <span class=" font-roboto text-black text-base md:text-lg font-normal leading-[150%]">Managing Director</span>
                    </div>
                    <p class=" font-roboto text-black text-base text-center max-w-[39rem] font-normal leading-[150%]">
                       Founded startups in gambling and sports prediction, as well as created partnerships with major operators and users in 56 countries. He was previously the founder and managing director of Nextwin, crypto trader and advisor on several crypto projects.
                    </p>
                    <div class=" flex items-center space-x-3">
                        <a href="" target="_blank" v-html="linkding"></a>
                        <a href=""  target="_blank" v-html="twitter"></a>
                    </div>
                </div>
                 <div class=" flex flex-col items-center space-y-4">
                    <div class=" w-20 h-20 rounded-full bg-gray-400 overflow-hidden">
                        <img src="/images/home/pmm.png" alt="">
                    </div>
                    <div class=" text-center">
                        <h1 class=" font-roboto text-black text-lg md:text-xl font-semibold leading-[150%]">Michele De Pasquale</h1>
                        <span class=" font-roboto text-black text-base md:text-lg font-normal leading-[150%]">Product Marketing Manager</span>
                    </div>
                    <p class=" font-roboto text-black text-base text-center max-w-[39rem] font-normal leading-[150%]">
                       Spent the last 12 years in product marketing within different industries. My focus has been on the design, development and operational implementation of products for an increase in revenue.
                    </p>
                    <div class=" flex items-center space-x-3">
                        <a href="" target="_blank" v-html="linkding"></a>
                        <a href=""  target="_blank" v-html="twitter"></a>
                    </div>
                </div>
                 <div class=" flex flex-col items-center space-y-4">
                    <div class=" w-20 h-20 rounded-full bg-gray-400 overflow-hidden">
                        <img src="/images/home/cto.png" alt="">
                    </div>
                    <div class=" text-center">
                        <h1 class=" font-roboto text-black text-lg md:text-xl font-semibold leading-[150%]">Fabio Di Sotto</h1>
                        <span class=" font-roboto text-black text-base md:text-lg font-normal leading-[150%]">CTO</span>
                    </div>
                    <p class=" font-roboto text-black text-base text-center max-w-[39rem] font-normal leading-[150%]">
                       He is a full-stack developer with 8 years of experience, specializing in developing blockchain dApps with Solidity and backend technologies like PHP, Python, Java, SQL, and NoSQL. They are also skilled in developing web interfaces using HTML5, CSS3, JavaScript (ES6), Typescript, and Vue.
                    </p>
                    <div class=" flex items-center space-x-3">
                        <a href="" target="_blank" v-html="linkding"></a>
                        <a href=""  target="_blank" v-html="twitter"></a>
                    </div>
                </div>
            </div>


            <div class=" flex flex-col items-center text-center space-y-4 md:pt-20">
                <h1 class=" text-black font-ubuntu text-[1.5rem] sm:text-[1.875rem] font-bold">We’re hiring!</h1>
                <span class=" font-ubuntu text-black text-base sm:text-xl font-light">See our open roles</span>
                 <div class=" w-full relative justify-center flex pt-4"> 
                    <div class="btn-blur absolute"></div>
                    <button class=" w-[12.32556rem!important] btn btn-shadow-1 relative z-10">Open Roles</button>
                </div>
            </div>
      </div>
   
        

    </section>
</template>


<script setup>
 const linkding = '<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"><path fill-rule="evenodd" clip-rule="evenodd" d="M4.5 3.24268C3.67157 3.24268 3 3.91425 3 4.74268V19.7427C3 20.5711 3.67157 21.2427 4.5 21.2427H19.5C20.3284 21.2427 21 20.5711 21 19.7427V4.74268C21 3.91425 20.3284 3.24268 19.5 3.24268H4.5ZM8.52076 7.2454C8.52639 8.20165 7.81061 8.79087 6.96123 8.78665C6.16107 8.78243 5.46357 8.1454 5.46779 7.24681C5.47201 6.40165 6.13998 5.72243 7.00764 5.74212C7.88795 5.76181 8.52639 6.40728 8.52076 7.2454ZM12.2797 10.0044H9.75971H9.7583V18.5643H12.4217V18.3646C12.4217 17.9847 12.4214 17.6047 12.4211 17.2246C12.4203 16.2108 12.4194 15.1959 12.4246 14.1824C12.426 13.9363 12.4372 13.6804 12.5005 13.4455C12.7381 12.568 13.5271 12.0013 14.4074 12.1406C14.9727 12.2291 15.3467 12.5568 15.5042 13.0898C15.6013 13.423 15.6449 13.7816 15.6491 14.129C15.6605 15.1766 15.6589 16.2242 15.6573 17.2719C15.6567 17.6417 15.6561 18.0117 15.6561 18.3815V18.5629H18.328V18.3576C18.328 17.9056 18.3278 17.4537 18.3275 17.0018C18.327 15.8723 18.3264 14.7428 18.3294 13.6129C18.3308 13.1024 18.276 12.599 18.1508 12.1054C17.9638 11.3713 17.5771 10.7638 16.9485 10.3251C16.5027 10.0129 16.0133 9.81178 15.4663 9.78928C15.404 9.78669 15.3412 9.7833 15.2781 9.77989C14.9984 9.76477 14.7141 9.74941 14.4467 9.80334C13.6817 9.95662 13.0096 10.3068 12.5019 10.9241C12.4429 10.9949 12.3852 11.0668 12.2991 11.1741L12.2797 11.1984V10.0044ZM5.68164 18.5671H8.33242V10.01H5.68164V18.5671Z" fill="black"/></svg>'
 const twitter = '<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"><path d="M17.1761 4.24268H19.9362L13.9061 11.0201L21 20.2427H15.4456L11.0951 14.6493L6.11723 20.2427H3.35544L9.80517 12.9935L3 4.24268H8.69545L12.6279 9.3553L17.1761 4.24268ZM16.2073 18.6181H17.7368L7.86441 5.78196H6.2232L16.2073 18.6181Z" fill="black"/></svg>'
</script>