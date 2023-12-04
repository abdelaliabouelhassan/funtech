<template>
   <div class=" w-full bg-white">
     <header class=" w-full flex items-center p-4    justify-between max-w-[1409px] mx-auto">
        <div>
            <nuxt-link to="/">
                <img src="/images/logo.svg" alt="">
            </nuxt-link>
        </div>
        
        
        <div class="  hidden items-center space-x-8 md:flex">
             <nuxt-link to="/" class="link">
                Solutions
            </nuxt-link>
            <nuxt-link to="/" class="link">
                About Us
            </nuxt-link>
            <nuxt-link to="/" class="link">
                News
            </nuxt-link>
           <div class=" relative">
             <nuxt-link to="/" class="link">
                Careers
            </nuxt-link>
            <img src="/images/wearehiring.svg" class=" absolute top-5 lg:top-0 w-full h-full lg:-right-16" alt="">
           </div>
        </div>


        <div class=" w-full max-w-[12.32556rem] hidden md:block">
            <nuxt-link to="/contact-us">
                 <button class="btn btn-shadow-1">Contact us</button>
            </nuxt-link>
           
        </div>

        <div class=" md:hidden">
            <button @click="show = true">
                <svg xmlns="http://www.w3.org/2000/svg" class=" w-10" viewBox="0 0 24 24" fill="none">
                   <path fill-rule="evenodd" clip-rule="evenodd" d="M12.3977 15.6629C12.178 15.8826 11.8219 15.8826 11.6022 15.6629L5.86739 9.92804C5.64772 9.70837 5.64772 9.35227 5.86739 9.13259L6.13256 8.86739C6.35222 8.64772 6.70838 8.64772 6.92805 8.86739L12 13.9393L17.0719 8.86739C17.2916 8.64772 17.6477 8.64772 17.8674 8.86739L18.1326 9.13259C18.3522 9.35227 18.3522 9.70837 18.1326 9.92804L12.3977 15.6629Z" fill="black"/>
                </svg>
             
            </button>
        </div>
    </header>
   </div>

      <aside id="default-sidebar" :class="{'translate-y-0':show,'-translate-y-full rtl:translate-y-full':!show}" class="fixed py-4 f-lg:hidden bg-white top-0 left-0 rtl:right-0 z-40 w-full  transition-transform  " aria-label="Sidebar">
            <div class="h-full  overflow-y-auto   ">
                <div class=" w-full flex flex-col items-center space-y-4">
                    <div class=" w-full flex items-center justify-between p-4">
                    <nuxt-link to="/">
                        <img src="/images/logo.svg" alt="">
                    </nuxt-link>
                    <button @click="show = false" class="  hover:text-secondary duration-300">
                           <svg xmlns="http://www.w3.org/2000/svg" class=" w-10" viewBox="0 0 24 24" fill="none">
                            <path d="M16.192 6.34424L11.949 10.5862L7.70697 6.34424L6.29297 7.75824L10.535 12.0002L6.29297 16.2422L7.70697 17.6562L11.949 13.4142L16.192 17.6562L17.606 16.2422L13.364 12.0002L17.606 7.75824L16.192 6.34424Z" fill="black"/>
                            </svg>
                    </button>
                </div>
                </div>
                <div class=" w-full flex">
                     <ul class="space-y-8 text-center font-medium py-8 m-auto">
                    <li>
                       <nuxt-link to="/" class="link">
                            Solutions
                     </nuxt-link>
                    </li>
                    <li>
                       <nuxt-link to="/" class="link">
                            About Us
                     </nuxt-link>

                    </li>
                    <li>
                       <nuxt-link to="/" class="link">
                            News
                     </nuxt-link>

                    </li>
                    <li>
                       <div class=" relative">
                            <nuxt-link to="/" class="link">
                                Careers
                            </nuxt-link>
                            <img src="/images/wearehiring.svg" class=" absolute  top-0 w-full h-full -right-[4.5rem]" alt="">
                        </div>
                    </li>

                </ul>
                </div>  
            </div>
     </aside>
</template>

<script setup>
 const show = ref(false)
</script>


<style scoped>
 .link {
    @apply  text-black font-ubuntu text-base font-normal hover:text-[#BC00AD] duration-200 whitespace-nowrap;
 }
</style>