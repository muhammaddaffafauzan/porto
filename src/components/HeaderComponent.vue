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
<div class="button">
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
      <a href="#" class="hover:underline">info@company.com</a>
   </p>
   <p class="text-sm text-gray-500 dark:text-gray-400">
      <a href="#" class="hover:underline">212-456-7890</a>
   </p>
</div>
   
   
  </div>
  <div class="basis-1/2">
    <img src="../assets/logo-daffa.png" class="header-img" alt="dafa">
   
  </div>
</div>
<!-- header -->
<svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 300" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(255, 0, 0, 1)" offset="0%"></stop><stop stop-color="rgba(45.856, 45.856, 45.856, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,60L24,95C48,130,96,200,144,235C192,270,240,270,288,255C336,240,384,210,432,185C480,160,528,140,576,130C624,120,672,120,720,130C768,140,816,160,864,150C912,140,960,100,1008,110C1056,120,1104,180,1152,195C1200,210,1248,180,1296,160C1344,140,1392,130,1440,115C1488,100,1536,80,1584,85C1632,90,1680,120,1728,110C1776,100,1824,50,1872,25C1920,0,1968,0,2016,10C2064,20,2112,40,2160,50C2208,60,2256,60,2304,95C2352,130,2400,200,2448,200C2496,200,2544,130,2592,100C2640,70,2688,80,2736,110C2784,140,2832,190,2880,210C2928,230,2976,220,3024,215C3072,210,3120,210,3168,200C3216,190,3264,170,3312,170C3360,170,3408,190,3432,200L3456,210L3456,300L3432,300C3408,300,3360,300,3312,300C3264,300,3216,300,3168,300C3120,300,3072,300,3024,300C2976,300,2928,300,2880,300C2832,300,2784,300,2736,300C2688,300,2640,300,2592,300C2544,300,2496,300,2448,300C2400,300,2352,300,2304,300C2256,300,2208,300,2160,300C2112,300,2064,300,2016,300C1968,300,1920,300,1872,300C1824,300,1776,300,1728,300C1680,300,1632,300,1584,300C1536,300,1488,300,1440,300C1392,300,1344,300,1296,300C1248,300,1200,300,1152,300C1104,300,1056,300,1008,300C960,300,912,300,864,300C816,300,768,300,720,300C672,300,624,300,576,300C528,300,480,300,432,300C384,300,336,300,288,300C240,300,192,300,144,300C96,300,48,300,24,300L0,300Z"></path></svg>
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
  font-size: 18px;
  margin-left: 80px;
  margin-top: 50px;
 }
 .text-header{
  font-size: 18px;
  margin-left: 80px;
 }
 .header-img{
  margin-left: 150px;
 }
 .button{
   width: 200px;
   margin-left: 80px;
   margin-top: 2%;
 }
}
</style>