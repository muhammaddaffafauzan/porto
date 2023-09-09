<template>
  <!-- header -->
<div class="flex flex-row flex-wrap" style="margin-top: 60px;">
  <div class="basis-1/2">
    <p class="judul-header">
    Hi! i'm muhammad daffa fauzan <br>
   </p>
   <p class="text-header">
  I'mLive in Bandung, Indonesia
  i'm 18 years old,
  i nowSoftware Engineering Student at Assalaam Vocational High School
  Maybe, Java Script is my favorite language <br>
   </p>
 <!-- drawer init and show -->
<div class="button pt-5 ">
   <button class="text-white bg-red-700 hover:bg-white-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800" type="button" data-drawer-target="drawer-contact" data-drawer-show="drawer-contact" aria-controls="drawer-contact">
    Contact Now
   </button>
   <a href="#" class="inline-flex justify-center items-center ml-5 py-2 px-3 text-base font-medium text-center text-gray-900 rounded-lg border border-gray-300 hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-700 dark:hover:bg-gray-700 dark:focus:ring-gray-800">
      Learn more
   </a>  
</div>         
 <!-- drawer component -->
<div id="drawer-contact" class="fixed top-0 left-0 z-40 h-screen p-4 overflow-y-auto transition-transform -translate-x-full bg-white w-80 dark:bg-gray-800" tabindex="-1" aria-labelledby="drawer-contact-label">
   <h5 id="drawer-label" class="inline-flex items-center mb-6 text-base font-semibold text-gray-500 uppercase dark:text-gray-400"><svg class="w-4 h-4 mr-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 16">
    <path d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z"/>
    <path d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z"/>
  </svg>Contact us</h5>
   <button type="button" data-drawer-hide="drawer-contact" aria-controls="drawer-contact" class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm w-8 h-8 absolute top-2.5 right-2.5 inline-flex items-center justify-center dark:hover:bg-gray-600 dark:hover:text-white" >
      <svg class="w-3 h-3" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14">
         <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 1 6 6m0 0 6 6M7 7l6-6M7 7l-6 6"/>
      </svg>
      <span class="sr-only">Close menu</span>
   </button>
   <form action="#" class="mb-6">
      <div class="mb-6">
         <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Your email</label>
         <input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="name@company.com" required>
      </div>
      <div class="mb-6">
         <label for="subject" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Subject</label>
         <input type="text" id="subject" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Let us know how we can help you" required>
      </div>
      <div class="mb-6">
         <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Your message</label>
         <textarea id="message" rows="4" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Your message..."></textarea>
      </div>
      <button type="submit" class="text-white bg-red-700 hover:bg-white-800 w-full focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800 block">Send message</button>
   </form>
   <p class="mb-2 text-sm text-gray-500 dark:text-gray-400">
      <a href="#" class="hover:underline">daffafauzan0405@gmail.com</a>
   </p>
   <p class="text-sm text-gray-500 dark:text-gray-400">
      <a href="#" class="hover:underline">+62 8953-8741-7000</a>
   </p>
</div>
   
   
  </div>
  <div class="basis-1/2">
    <img src="../assets/logo-daffa.png" class="header-img" alt="dafa">
   
  </div>
</div>
<!-- header -->
<svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 290" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(255, 0, 0, 1)" offset="0%"></stop><stop stop-color="rgba(18.534, 18.534, 18.534, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,29L48,53.2C96,77,192,126,288,135.3C384,145,480,116,576,130.5C672,145,768,203,864,217.5C960,232,1056,203,1152,203C1248,203,1344,232,1440,207.8C1536,184,1632,106,1728,67.7C1824,29,1920,29,2016,53.2C2112,77,2208,126,2304,125.7C2400,126,2496,77,2592,91.8C2688,106,2784,184,2880,212.7C2976,242,3072,222,3168,193.3C3264,164,3360,126,3456,91.8C3552,58,3648,29,3744,53.2C3840,77,3936,155,4032,183.7C4128,213,4224,193,4320,183.7C4416,174,4512,174,4608,169.2C4704,164,4800,155,4896,130.5C4992,106,5088,68,5184,77.3C5280,87,5376,145,5472,145C5568,145,5664,87,5760,87C5856,87,5952,145,6048,183.7C6144,222,6240,242,6336,236.8C6432,232,6528,203,6624,188.5C6720,174,6816,174,6864,174L6912,174L6912,290L6864,290C6816,290,6720,290,6624,290C6528,290,6432,290,6336,290C6240,290,6144,290,6048,290C5952,290,5856,290,5760,290C5664,290,5568,290,5472,290C5376,290,5280,290,5184,290C5088,290,4992,290,4896,290C4800,290,4704,290,4608,290C4512,290,4416,290,4320,290C4224,290,4128,290,4032,290C3936,290,3840,290,3744,290C3648,290,3552,290,3456,290C3360,290,3264,290,3168,290C3072,290,2976,290,2880,290C2784,290,2688,290,2592,290C2496,290,2400,290,2304,290C2208,290,2112,290,2016,290C1920,290,1824,290,1728,290C1632,290,1536,290,1440,290C1344,290,1248,290,1152,290C1056,290,960,290,864,290C768,290,672,290,576,290C480,290,384,290,288,290C192,290,96,290,48,290L0,290Z"></path></svg>
</template>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@900&display=swap');
 .judul-header{
  font-family: 'Montserrat', sans-serif;
  font-size: 25px;
  margin-left: 100px;
  margin-top: 50px;
 }
 .text-header{
  font-size: 15px;
  margin-left: 100px;
 }
 .header-img{
 margin-left: 200px;

 }
 .button{
   margin-left: 15%;
 }
 @media only screen and (max-width: 500px) {
   .judul-header{
  font-family: 'Montserrat', sans-serif;
  font-size: 15px;
  margin-left: 80px;
  margin-top: 50px;
 }
 .text-header{
  font-size: 12px;
  margin-left: 80px;
 }
 .header-img{
  margin-left: 100px;
  width: auto;
 }
 .button{
   width: 300px;
   margin-left: 80px;
   margin-top: 2%;
 }
}
</style>