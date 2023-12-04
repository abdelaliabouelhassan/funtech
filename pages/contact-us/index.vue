<template>
    <div class=" w-full">
        <FirstSection />
        <SecondSection />
        <div class=" w-full h-[20.375rem] bg-effect md:pt-[25rem] hidden md:block">

        </div>
     

    </div>
</template>


<script setup>
 import FirstSection from "~/components/partials/sections/contact-us/FirstSection.vue";
 import SecondSection from "~/components/partials/sections/contact-us/SecondSection.vue";
 import ThirdSection from "~/components/partials/sections/home/TenthSection.vue";
</script>

<style scoped>
 .bg-effect {
    background: linear-gradient(180deg, #F6F2FF 0%, #100146 100%);
 }
</style>