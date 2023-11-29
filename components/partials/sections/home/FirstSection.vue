<template>
    <section id="first-section" class=" w-full px-4">
        <p class=" max-w-[72.6875rem]  mx-auto text-[2.5rem] md:text-[4rem] lg:text-[5rem] font-ubuntu text-center font-light leading-[150%] text-[#100146]">
            We have found the balance between <span class=" font-bold">Scalability, Security</span> and <span class=" font-bold">Decentralized Innovation</span>
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
	trigger:"#first-section",
	// start:"top 60%",
	// end:"+=600",
    start:( () => {
        if(window.innerWidth >= 1144){
        return "top 60%"
        }else{
        return "top 10%"
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
	markers:true,
    pin:true,
    scrub:1
}})
.from("#first-section p", {y:-200,opacity:0, duration:1})
//.from("#first-section p", {scale:0, duration:1}, "<")
.to("#first-section p", {scale:1,opacity:1, duration:1})


})

</script>