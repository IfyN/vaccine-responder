<template>
<div class="flex flex-col items-center">
    <h1 class="text-2xl md:text-3xl mb-10 lg:mb-12 mt-6 font-semibold text-center">
     Find a location to get the COVID-19 Vaccine
 </h1>
<div class="mb-10 lg:mb-12">
    <div class="flex flex-col">
<!--Form section-->
       <form class="flex flex-row" action="/near-me" method="GET">
          <div class="relative input-location">
         <input type="text" id="vaclocation" name="city" class="rounded-full search-input border border-gray-300 hover:border-gray-400 focus:outline-none focus:border-gray-700f px-4 py-2 md:w-64" autocomplete="off" placeholder="Enter location...">
         
         <button class="rounded-full bg-blue-500 text-white hover:bg-blue-700 px-10 md:px-5 ms-2" id= "submit-city">Find Vaccine</button>  
           </div>
       </form>
    </div>
</div>
 

 <div class="max-w-4xl content-center grid md:grid-cols-2">
     <img src="https://res.cloudinary.com/ifeoma/image/upload/v1624989165/Fresh_Folk_-_Strolling_znbmwe.png" alt=" illustration of people">
 
 <div class="self-center text-black md:text-lg">
<p>

Everyone over 16 is now eligible for free, safe, and reliable COVID-19 vaccines in Lagos state. But it can be difficult to find out where and how to get a shot. Enter your city name to find confirmed vaccination locations near you, and learn how to make an appointment.      
</p>
 </div>
 </div>
 </div>
</template>

<style scoped>


</style>