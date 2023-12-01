<template>
    <section id="fifth-section" class=" w-full px-4">
        <p class=" max-w-[82rem]  mx-auto text-[2.5rem] md:text-[4rem] lg:text-[5rem] font-ubuntu text-center font-bold leading-[150%] text-[#100146]">
            How can Decentralization 
            benefit your industry?
        </p>
    </section>
</template>



<script setup>
import {gsap} from 'gsap'
import scrollTrigger from 'gsap/ScrollTrigger'
gsap.registerPlugin(scrollTrigger)

gsap.defaults({ease:"power1.out", duration:1})


onMounted(() => {
    let tl = gsap.timeline({scrollTrigger:{
	trigger:"#fifth-section",
	// start:"top 60%",
	// end:"+=600",
    start:( () => {
        if(window.innerWidth >= 1144){
        return "top 60%"
        }else{
        return "top 40%"
        }
    })(),
	end: (()=>{
        if(window.innerWidth >= 1144){
        return "+=900"
        }else{
        return "+=700"
        }
    })(),
	//toggleActions:"restart none none reverse",
	markers:false,
    pin:true,
    scrub:1
}})
.from("#fifth-section p", {y:-100,opacity:0, duration:1})
.from("#fifth-section p", {scale:0.7, duration:1}, "<")
.to("#fifth-section p", {scale:1,opacity:1, duration:1})


})

</script>