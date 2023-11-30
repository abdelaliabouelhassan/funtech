<template>
    <div class=" w-full">
        <HeroSection />
        <FirstSection />
        <SecondSection />
        <ThirdSection />
        <FourthSection />
    </div>
</template>


<script setup>
 import HeroSection from "~/components/partials/sections/home/HeroSection.vue";
 import FirstSection from "~/components/partials/sections/home/FirstSection.vue";
 import SecondSection from "~/components/partials/sections/home/SecondSection.vue";
 import ThirdSection from "~/components/partials/sections/home/ThirdSection.vue";
 import FourthSection from "~/components/partials/sections/home/FourthSection.vue";
</script>