<script setup>
import { ref } from 'vue'
import NavBar  from './components/NavBar.vue'




</script>

<template> 
<NavBar />

<div class="landing-screen">

<div class="flex justify-between z-20">
  <div class=" h-[100vh] w-[50%]">
    <div class="relative z-40 mt-48 ml-32">
        <div class="text-[68px] leading-[80px] text-white">Next</div>
        <div class="text-[68px] leading-[80px] text-white">Generation</div>
        <div class="text-[68px] leading-[80px] text-yellow-400 font-bold">Lottery</div>
        <div class="text-lg text-gray-400">The fastest lottery  in the web3 ecosystem with a new Draw every 5 minutes!</div>
    
     <div class=" w-[300px] mt-12 -rotate-12 relative buy-ticket-button">
      <img class="" src="./assets/ticket-btn.png" alt="">
      <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
        <div class="text-[22px] normal-font text-black font-bold bg-yellow-400 border-b-4 border-l-4 text-center border-yellow-500 px-4 py-2 w-[220px] rounded-xl">Buy Ticket</div>
      </div>

    </div>

    
      </div>

   
  </div>
  <div class=" h-[100vh] w-[50%] ">
    <div class="relative z-40 mt-32 mr-32">
        <div class="text-center text-[26px] text-white">Win up to <span class="text-[38px] font-bold text-gold"> $50.000 </span>  every 5 minutes</div>
        <img class="block m-auto w-[60%]  mt-12" src="./assets/Screenshot_2023-02-18_at_4.44.46_PM-removebg-preview.png" alt="">
    </div>
  </div>
</div>


  <div>
    <div class="custom-shape-divider-top-1676728505">

      <div class="relative">
        


        <svg class="top-waves" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path id="wave-1" d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" class="shape-fill"></path>
            <path id="wave-2" d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" class="shape-fill"></path>
            <path id="wave-3" d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" class="shape-fill"></path>
        </svg>
      </div>
       

    </div>

    <div class="custom-shape-divider-bottom-1676728737">

    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" class="shape-fill"></path>
        <path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" class="shape-fill"></path>
        <path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" class="shape-fill"></path>
    </svg>

</div>
</div>

</div>

<div class="h-[100vh] betting-screen relative">

  <div class="custom-shape-divider-top-222 absolute">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" class="shape-fill"></path>
        <path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" class="shape-fill"></path>
        <path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" class="shape-fill"></path>
    </svg>
    </div>




    <div class="h-[35%] relative pt-12">
      <div class="text-center text-[60px] font-bold text-gold ">$50.000</div>
      <div class="text-center text-gray-300 text-2xl "> <span class="text-[30px] font-bold text-yellow-500 ">5</span> minutes until the draw!</div>
      <div class="text-[22px] mt-16 normal-font m-auto text-black font-bold bg-yellow-400 border-b-4 border-l-4 text-center border-yellow-500 px-4 py-2 w-[220px] rounded-xl">Buy Ticket</div>

    </div>


    <div class="h-[65%]  relative flex justify-evenly align-middle items-center">

      <div class="bg-slate-900 w-[30%] h-[40%] rounded-3xl" >
        
         <div class=" py-2 bg-slate-800 rounded-t-3xl flex justify-between items-center align-middle">
          <div class="w-1/3 h-full text-white ml-3  rounded-tl-3xl"> #1233</div>
          <div class="w-1/3 h-full text-center text-lg whitespace-nowrap text-gray-400"> Finished Game</div>
          <div class="w-1/3 h-full  rounded-tr-3xl text-right mr-3"> 
            <div class="text-xs text-gray-400">round ended at</div>
            <div class="text-white">21:40</div>
          </div>
         </div>

         <div class=" mt-12 flex gap-4 justify-center items-center align-middle">
          <div class="w-12 h-12 border-4 border-red-700 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 8 </div>
          </div>
          <div class="w-12 h-12 border-4 border-green-700 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 12 </div>
          </div>
          <div class="w-12 h-12 border-4 border-blue-700 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 7 </div>
          </div>
          <div class="w-12 h-12 border-4 border-orange-500 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 3 </div>
          </div>
          <div class="w-12 h-12 border-4 border-yellow-600 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 14 </div>
          </div>
        
         </div>


      </div>
      <div class="bg-slate-900 w-[30%]  rounded-3xl " >

         <div class=" py-2 bg-slate-800 rounded-t-3xl flex justify-between items-center align-middle">
          <div class="w-1/3 h-full text-white ml-3  rounded-tl-3xl"> #1234</div>
          <div class="w-1/3 h-full text-center text-lg whitespace-nowrap text-gray-400"> Current Game</div>
          <div class="w-1/3 h-full  rounded-tr-3xl text-right mr-3"> 
            <div class="text-xs text-gray-400">round ends in</div>
            <div class="text-white">3:45</div>
          </div>
         </div>

         <div class=" mt-6 flex gap-4 justify-center items-center align-middle">
          <div class="w-12 h-12 border-4 border-red-700 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 
              <svg class="block m-auto" width="25px" height="25px" viewBox="0 0 8 8" id="meteor-icon-kit__regular-plus-xxs" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M3 3V0.83333C3 0.3731 3.4477 0 4 0C4.5523 0 5 0.3731 5 0.83333V3H7.1667C7.6269 3 8 3.4477 8 4C8 4.5523 7.6269 5 7.1667 5H5V7.1667C5 7.6269 4.5523 8 4 8C3.4477 8 3 7.6269 3 7.1667V5H0.83333C0.3731 5 0 4.5523 0 4C0 3.4477 0.3731 3 0.83333 3H3z" fill="#758CA3"/></svg>
                  
            </div>
          </div>
          <div class="w-12 h-12 border-4 border-green-700 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center "> 
              <svg class="block m-auto" width="25px" height="25px" viewBox="0 0 8 8" id="meteor-icon-kit__regular-plus-xxs" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M3 3V0.83333C3 0.3731 3.4477 0 4 0C4.5523 0 5 0.3731 5 0.83333V3H7.1667C7.6269 3 8 3.4477 8 4C8 4.5523 7.6269 5 7.1667 5H5V7.1667C5 7.6269 4.5523 8 4 8C3.4477 8 3 7.6269 3 7.1667V5H0.83333C0.3731 5 0 4.5523 0 4C0 3.4477 0.3731 3 0.83333 3H3z" fill="#758CA3"/></svg>
               </div>
          </div>
          <div class="w-12 h-12 border-4 border-blue-700 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center ">
              <svg class="block m-auto" width="25px" height="25px" viewBox="0 0 8 8" id="meteor-icon-kit__regular-plus-xxs" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M3 3V0.83333C3 0.3731 3.4477 0 4 0C4.5523 0 5 0.3731 5 0.83333V3H7.1667C7.6269 3 8 3.4477 8 4C8 4.5523 7.6269 5 7.1667 5H5V7.1667C5 7.6269 4.5523 8 4 8C3.4477 8 3 7.6269 3 7.1667V5H0.83333C0.3731 5 0 4.5523 0 4C0 3.4477 0.3731 3 0.83333 3H3z" fill="#758CA3"/></svg>
              
            </div>
          </div>
          <div class="w-12 h-12 border-4 border-orange-500 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center ">
              <svg class="block m-auto" width="25px" height="25px" viewBox="0 0 8 8" id="meteor-icon-kit__regular-plus-xxs" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M3 3V0.83333C3 0.3731 3.4477 0 4 0C4.5523 0 5 0.3731 5 0.83333V3H7.1667C7.6269 3 8 3.4477 8 4C8 4.5523 7.6269 5 7.1667 5H5V7.1667C5 7.6269 4.5523 8 4 8C3.4477 8 3 7.6269 3 7.1667V5H0.83333C0.3731 5 0 4.5523 0 4C0 3.4477 0.3731 3 0.83333 3H3z" fill="#758CA3"/></svg>
              
            </div>
          </div>
          <div class="w-12 h-12 border-4 border-yellow-600 bg-slate-300 rounded-full flex items-center font-bold">
            <div class="w-full text-lg text-center ">
              <svg class="block m-auto" width="25px" height="25px" viewBox="0 0 8 8" id="meteor-icon-kit__regular-plus-xxs" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M3 3V0.83333C3 0.3731 3.4477 0 4 0C4.5523 0 5 0.3731 5 0.83333V3H7.1667C7.6269 3 8 3.4477 8 4C8 4.5523 7.6269 5 7.1667 5H5V7.1667C5 7.6269 4.5523 8 4 8C3.4477 8 3 7.6269 3 7.1667V5H0.83333C0.3731 5 0 4.5523 0 4C0 3.4477 0.3731 3 0.83333 3H3z" fill="#758CA3"/></svg>
              
            </div>
          </div>
        
         </div>


        
         <div class="m-8 pt-4 p-8 rounded-3xl bg-slate-800 flex-grow ">
          <div class="text-center text-gray-400 mb-4 text-sm">Select 5 numbers</div>
          <div class="grid gap-2 grid-cols-5">
             <div v-for="num in [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]" 
              class="bg-gray-300 h-8 rounded-md text-center flex justify-center items-center cursor-pointer hover:bg-gray-400">  
              {{ num }}
            </div>
          </div>
         
         </div>

        

      </div>
      <div class="bg-slate-900 w-[30%] h-[40%] rounded-3xl" >
         <div class=" py-2 bg-slate-800 rounded-t-3xl flex justify-between items-center align-middle">
          <div class="w-1/3 h-full text-white ml-3  rounded-tl-3xl"> #1235</div>
          <div class="w-1/3 h-full text-center text-lg whitespace-nowrap text-gray-400"> Next Game</div>
          <div class="w-1/3 h-full  rounded-tr-3xl text-right mr-3"> 
            <div class="text-xs text-gray-400">round starts at</div>
            <div class="text-white">21:45</div>
          </div>
         </div>


         <div class=" mt-12 flex gap-4 justify-center items-center align-middle">
          <div class="w-10 h-10 bg-slate-300 rounded-full"></div>
          <div class="w-10 h-10 bg-slate-300 rounded-full"></div>
          <div class="w-10 h-10 bg-slate-300 rounded-full"></div>
         </div>

      </div>
      
    </div>


</div>


<div>

  <div class="custom-shape-divider-top-1676739897">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M600,112.77C268.63,112.77,0,65.52,0,7.23V120H1200V7.23C1200,65.52,931.37,112.77,600,112.77Z" class="shape-fill"></path>
    </svg>
</div>

<div class="text-2xl text-gray-300 text-center">Are you a Winner?</div>

<div class="text-lg w-[200px] font-bold text-center py-2 mt-6 rounded-xl text-gray-300 bg-[#3c124b] border border-b-4 border-[#2f0e3a] m-auto">Check Now</div>


<div class="custom-shape-divider-top-333">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M600,112.77C268.63,112.77,0,65.52,0,7.23V120H1200V7.23C1200,65.52,931.37,112.77,600,112.77Z" class="shape-fill"></path>
    </svg>
</div>

<div class="custom-shape-divider-top-444">
    <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
        <path d="M600,112.77C268.63,112.77,0,65.52,0,7.23V120H1200V7.23C1200,65.52,931.37,112.77,600,112.77Z" class="shape-fill"></path>
    </svg>
</div>

<div id="how-to-play" class="text-yellow-400 text-[38px] text-center"> How To Play</div>

<div class="text-xl text-gray-300 text-center w-[60%] mt-8 m-auto">If the digits on your tickets match the winning 
  numbers in the correct order, you win a portion of the prize pool.
<br/>  Simple!</div>


<div class="flex justify-evenly items-center align-middle text-gray-300 mt-24 w-[80%] m-auto ">

  <div class="w-1/4 h-[150px] bg-[#3c124b] rounded-xl border-l-4 border-b-4 border-[#4e1563] p-4 pb-4">
    <div class="text-right text-sm font-bold -mt-2">STEP 1</div>
    <div class="text-center my-4 text-white text-xl font-bold">Buy Tickets</div>
    <div class="text-center text-sm text-[#BFBFAA] mt-2">Prices are set when the round starts, equal to 5 USD in BNB per ticket.</div>
  </div>
  <div class="w-1/4 h-[150px] bg-[#3c124b] rounded-xl border-l-4 border-b-4 border-[#4e1563] p-4 pb-4">
    <div class="text-right text-sm font-bold -mt-2">STEP 2</div>
    <div class="text-center my-4 text-white text-xl font-bold">Wait for the Draw</div>
    <div class="text-center text-sm text-[#BFBFAA] mt-2">There is one draw every 5 minutes.</div>
  </div>
  <div class="w-1/4 h-[150px] bg-[#3c124b] rounded-xl border-l-4 border-b-4 border-[#4e1563] p-4 pb-4">
    <div class="text-right text-sm font-bold -mt-2">STEP 3</div>
    <div class="text-center my-4 text-white text-xl font-bold">Check for Prizes</div>
    <div class="text-center text-sm text-[#BFBFAA] mt-2">Once the round’s over check to see if you’ve won!</div>
  </div>

</div>


<div class="w-[80%] m-auto">

  <!-- a horizontal line -->
  <div class="border border-slate-600  m-auto mt-24 "></div>

  <div class="text-yellow-400 text-[38px] mt-16 text-left"> Winning Criteria</div>

  <div class="text-xl text-gray-300 text-left  mt-8  w-[60%]">The digits on your ticket must match in the correct order to win.</div>

  <div class="text-sm text-[#BFBFAA] text-left  mt-8  w-[60%]">
    Here’s an example lottery draw, with two tickets, A and B.
Ticket A: The first 3 digits and the last 2 digits match, but the 4th digit is wrong, so this ticket only wins a “Match first 3” prize.
Ticket B: Even though the last 5 digits match, the first digit is wrong, so this ticket doesn’t win a prize.
Prize brackets don’t ‘stack’: if you match the first 3 digits in order, you’ll only win prizes from the ‘Match 3’ bracket, and not from ‘Match 1’ and ‘Match 2’.
  </div>


</div>


<footer class="mt-24 h-[200px] relative">

  <svg class="custom-shape-divider-top-444 absolute bottom-0" height="200"  data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none" >
    <path  d="M0,0V7.23C0,65.52,268.63,112.77,600,112.77S1200,65.52,1200,7.23V0Z"  fill="#2D1835" fill-opacity="1"></path>
  </svg>

  <div class="absolute bottom-0 flex justify-between items-end align-bottom w-full px-48 pb-4 ">
    <div class="text-[32px] leading-[80px] text-yellow-400 font-bold">Lottery</div>

    <div class="text-white text-center text-sm font-bold">© 2021 Lottery</div>

    <div>
      <a class="text-[#55554c] underline block mb-2 " href=""> Contact Us </a>
      <a class="text-[#55554c]  underline block mb-2 " href=""> White Paper </a>
      <a class="text-[#55554c]  underline block mb-2 " href=""> Source Code </a>


    </div>
  </div>

</footer>


</div>



</template>

<style scoped>

</style>
