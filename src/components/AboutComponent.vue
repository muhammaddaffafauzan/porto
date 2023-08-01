<template>
 
  <svg id="wave" style="transform:rotate(180deg); transition: 0.3s" viewBox="0 0 1440 150" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(255, 0, 0, 1)" offset="0%"></stop><stop stop-color="rgba(45.856, 45.856, 45.856, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,30L34.3,47.5C68.6,65,137,100,206,117.5C274.3,135,343,135,411,127.5C480,120,549,105,617,92.5C685.7,80,754,70,823,65C891.4,60,960,60,1029,65C1097.1,70,1166,80,1234,75C1302.9,70,1371,50,1440,55C1508.6,60,1577,90,1646,97.5C1714.3,105,1783,90,1851,80C1920,70,1989,65,2057,57.5C2125.7,50,2194,40,2263,42.5C2331.4,45,2400,60,2469,55C2537.1,50,2606,25,2674,12.5C2742.9,0,2811,0,2880,5C2948.6,10,3017,20,3086,25C3154.3,30,3223,30,3291,47.5C3360,65,3429,100,3497,100C3565.7,100,3634,65,3703,50C3771.4,35,3840,40,3909,55C3977.1,70,4046,95,4114,105C4182.9,115,4251,110,4320,107.5C4388.6,105,4457,105,4526,100C4594.3,95,4663,85,4731,85C4800,85,4869,95,4903,100L4937.1,105L4937.1,150L4902.9,150C4868.6,150,4800,150,4731,150C4662.9,150,4594,150,4526,150C4457.1,150,4389,150,4320,150C4251.4,150,4183,150,4114,150C4045.7,150,3977,150,3909,150C3840,150,3771,150,3703,150C3634.3,150,3566,150,3497,150C3428.6,150,3360,150,3291,150C3222.9,150,3154,150,3086,150C3017.1,150,2949,150,2880,150C2811.4,150,2743,150,2674,150C2605.7,150,2537,150,2469,150C2400,150,2331,150,2263,150C2194.3,150,2126,150,2057,150C1988.6,150,1920,150,1851,150C1782.9,150,1714,150,1646,150C1577.1,150,1509,150,1440,150C1371.4,150,1303,150,1234,150C1165.7,150,1097,150,1029,150C960,150,891,150,823,150C754.3,150,686,150,617,150C548.6,150,480,150,411,150C342.9,150,274,150,206,150C137.1,150,69,150,34,150L0,150Z"></path></svg>
<div id="about"></div>
<!-- <div class="box-border" style="width: 1200px; height: 500px; margin-left: 70px; background-color: rgba(255, 255, 255, 0.892); "> -->
  <div class="flex flex-row flex-wrap">
  <div class="basis-1/2">
     <p class="about">
      About me
     </p>
     <p class="text-about">
    &ensp;&ensp; I am Muhammad Daffa Fauzan, I am now 18 years old, my career is graduating from elementary school at SDN Jatimekar, graduating from junior high school at SMPN 3 Baleendah and currently still a student at SMK Assalaam Bandung, majoring in Software Engineering (RPL), I have 2 brothers, I am an older brother and 1 son -My younger brother is still an elementary school student. I was born in a simple happy family. My goal is to become a successful young entrepreneur, Amin.
     </p>
  </div>
  <div class="basis-1/2">
    
      <div class="grid grid-cols-1 gap-1">
        <div class="img">
            <img class="h-50 w-72 rounded-lg" src="../assets/image/pt1.jpg" alt="">
        </div>
    </div>

</div>
</div>
<!-- </div> -->
</template>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Rubik+Mono+One&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');
.about{
  font-family: 'Rubik Mono One', sans-serif;
  position: relative;
  margin-left: 70px;
  font-size: 30px;
}
.text-about{
  margin-left: 15px;
  font-family: 'Poppins', sans-serif;
  text-align: left;
  text-align: justify;
}

@media only screen and (max-width: 500px) {
  .img{
    margin-top: 10%;
    margin-right: 5%;
  }
  .text-about{
    font-size: 10px;
    margin-right: 10%;
  }
  .about{
    font-size: 15px;
    margin-left: 20%;
  }
}
@media only screen and (min-width: 1000px) {
  .img{
  width: 300px;
  margin-top: 50px;
  margin-left: 180px;

  }
  .text-about{
    font-size: 20px;
    margin-left: 10%;
  }
  .about{
    font-size: 35px;
    margin-left: 15%;
  }
}
</style>