<template>
    <section class=" w-full bg-[#F9F9FF]  overflow-hidden py-10 md:py-28 px-4">
        <div class=" flex flex-col items-center space-y-4 max-w-[48rem] mx-auto">
            <span class=" text-[#100146] font-ubuntu text-center text-base font-medium leading-[150%]">Revolutionize</span>
            <h1 class=" text-[#100146] text-center font-ubuntu text-[2.25rem] md:text-[3rem] font-bold leading-[120%]">Get in Touch</h1>
            <p class=" text-center text-[#100146] font-ubuntu text-base md:text-lg leading-[150%] font-normal">
                Have a question or comment? We'd love to hear from you.
            </p>

          <form action="" class=" w-full">
              <div class=" w-full grid grid-cols-2 gap-x-5 gap-y-7 pt-10">
                <div class=" flex flex-col items-start space-y-2">
                    <label for="first" class=" text-black font-ubuntu text-base">First Name</label>
                    <input type="text" name="" id="first" placeholder="First Name" class=" placeholder-[#505050] font-roboto text-base font-normal outline-none h-12 w-full p-3 border border-black bg-white">
                </div>
                 <div class=" flex flex-col items-start space-y-2">
                    <label for="last" class=" text-black font-ubuntu text-base">Last Name</label>
                    <input type="text" name="" id="last" placeholder="Last Name" class=" placeholder-[#505050] font-roboto text-base font-normal outline-none h-12 w-full p-3 border border-black bg-white">
                </div>
                 <div class=" flex flex-col items-start col-span-2 md:col-span-1 space-y-2">
                    <label for="Email" class=" text-black font-ubuntu text-base">Email</label>
                    <input type="email" name="" id="Email" placeholder="Email" class=" placeholder-[#505050] font-roboto text-base font-normal outline-none h-12 w-full p-3 border border-black bg-white">
                </div>
                 <div class=" flex flex-col items-start col-span-2 md:col-span-1 space-y-2">
                    <label for="Phone" class=" text-black font-ubuntu text-base">Phone Number</label>
                    <input type="tele" name="" id="Phone" placeholder="Phone Number" class=" placeholder-[#505050] font-roboto text-base font-normal outline-none h-12 w-full p-3 border border-black bg-white">
                </div>
                 <div class=" flex flex-col items-start space-y-2 col-span-2">
                    <label for="Message" class=" text-black font-ubuntu text-base">Message</label>
                   <textarea name="" id="Message" cols="30" rows="10" placeholder="Type Your Message..." class=" placeholder-[#505050] font-roboto text-base font-normal outline-none h-[11.25rem] w-full p-3 border border-black bg-white"></textarea>
                </div>
            </div>
            <div class=" w-full flex pt-5">
                <button class=" m-auto hover:scale-110 duration-200 font-roboto text-base font-normal text-white bg-black border border-black w-[6.1875rem] h-12">Button</button>
            </div>
          </form>
        </div>

      
    </section>
</template>

