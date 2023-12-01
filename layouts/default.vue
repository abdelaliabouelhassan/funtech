<template>
    <div class=" w-full overflow-hidden bg-[#F6F2FF]">
        <Header />
        <slot></slot>
        <Footer />
    </div>
</template>

<script setup>
  import Header from '~/components/partials/Header.vue'
  import Footer from '~/components/partials/Footer.vue'
</script>