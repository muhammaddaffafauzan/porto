<template>
 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#E70000" fill-opacity="1" d="M0,64L30,80C60,96,120,128,180,122.7C240,117,300,75,360,85.3C420,96,480,160,540,165.3C600,171,660,117,720,128C780,139,840,213,900,208C960,203,1020,117,1080,85.3C1140,53,1200,75,1260,90.7C1320,107,1380,117,1410,122.7L1440,128L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"></path></svg>
     <div class="indikator">
    <div class="flex flex-row text-white gap-4">
  <div class="basis-1/2">
  <p class="text-center font-bold text-6xl">
   5+ <br>
   <span class="text-center font-medium text-2xl">Project</span>
  </p>
  </div>
  <div class="basis-1/2">
    <p class="text-center font-bold text-6xl">
   01 <br>
   <span class="text-center font-medium text-2xl">Year Experience</span>
  </p>
  </div>
  <div class="basis-1/2">
    <p class="text-center font-bold text-6xl">
   0 <br>
   <span class="text-center font-medium text-2xl">achievement</span>
  </p>
  </div>
</div>
</div>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#E70000 " fill-opacity="1" d="M0,128L80,122.7C160,117,320,107,480,112C640,117,800,139,960,160C1120,181,1280,203,1360,213.3L1440,224L1440,0L1360,0C1280,0,1120,0,960,0C800,0,640,0,480,0C320,0,160,0,80,0L0,0Z"></path></svg>
  
  <div class="skills-section">
    <div class="skills-header font-bold" id="skills">
     <h1>My Skills</h1>   
     </div>
     <div class="skills-container">
       
      <div class="skills-box">
       <div class="skills-title">
       <div class="skills-img">
        <img src="https://cdn.freebiesupply.com/logos/large/2x/html-5-logo-png-transparent.png"     alt="" class="skills-icons">
        </div>
         <h3 class="font-bold">HTML 5</h3>

        </div>
       </div>
       
       
        <div class="skills-box">
       <div class="skills-title">
       <div class="skills-img">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3d/CSS.3.svg" alt="" class="skills-icons">
        </div>
        <h3 class="font-bold">CSS3</h3>
        </div>   
       </div>
       
       
        <div class="skills-box">
       <div class="skills-title">
       <div class="skills-img">
        <img src="https://icon-library.net/images/javascript-icon-png/javascript-icon-png-23.jpg" alt="" class="skills-icons">
        </div>
        <h3 class="font-bold">JAVASCRIPT</h3>
        </div>
       </div>
       
          <div class="skills-box">
       <div class="skills-title">
       <div class="skills-img">
        <img src="http://pluspng.com/img-png/nodejs-logo-png-nice-images-collection-node-js-desktop-wallpapers-370.png" alt="" class="skills-icons">
        </div>
        <h3 class="font-bold">NODE.JS</h3>
        </div>
       </div>
       
          <div class="skills-box">
       <div class="skills-title">
       <div class="skills-img">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/555px-Vue.js_Logo_2.svg.png" alt="" class="skills-icons">
        </div>
        <h3 class="font-bold">Vue.js</h3>
        </div>
       </div>
       </div>
    
     </div>

</template>

<style>
*{
padding: 0;
margin: 0;
box-sizing: border-box;
font-family: Arial, sans-serif;
}

.skills-section{
padding-top: 20px;
}

.skills-header{
text-align: center;
font-size: x-large;
color: #000000;
padding: 1rem;
position: relative;
}

.skills-header:after{
content: '';
position: absolute;
bottom: 0;
left: 50%;
transform: translateX(-50%);
width: 100px;
height: 4px;
background-color: #E70000;
border-radius: 2px;
}

.skills-container{
display: grid;
grid-tempLate-columns: repeat(5, 1fr);
justify-content:center;
align-items:center;
text-align: center;
grid-gap:1rem;
padding: 1rem 80px;
font-size: 1.2rem;
}
.skills-box{
padding: 1rem;
color: #000;
cursor:pointer;
}
/* .skills-box:hover > .skills-title: after, 
.skills-box:hover > .skills-title: before{
width: 30px;
} */
.skills-box:hover .skills-img{
transform: translateX(-20px);
}

.skills-title{
display:flex;
flex-direction: column;
align-items:center;
padding: 0.5rem;
margin-bottom: 0.5rem;
position: relative;
}

.skills-title:after{
content: '';
position:absolute;
bottom: 0;
right: 50%;
width:20px;
height:4px;
border-radius: 2px 0 0 2px;

transition: .5s;
}

.skills-title:before{
content: '';
position:absolute;
bottom: 0;
left: 50%;
width:100px;
height:4px;
border-radius: 0 2px 2px 0;

}

.skills-icons{
width:50px;
z-index:2;
}

.skills-img{
width:90px;
height:90px;
position: relative;
border-radius: 45px;
background-color: #E70000;
display:flex;
justify-content:center;
align-items:center;
transition: .5s;
}

.skills-img:after{
content: '';
position:absolute;
top:0;
left: 0;
width:50%;
height:90px;
background: rgba(100, 100, 100, 0.5);
border-radius: 45px 0 0 45px;
}
.skills-title h3{
color: #333;
margin-top: 0.5rem;
}
.indikator{
  background-color: #E70000;
}
@media screen and (max-width:990px){
 .skills-container{
 grid-tempLate-columns: repeat(2, 1fr);
 padding: 2rem 50px;
 }
}

@media screen and (max-width:650px){
 .skills-container{
 grid-tempLate-columns:2fr;
 padding: 2rem 50px;
 }
}
@media screen and (max-width:500px){
 .indikator{
  font-size: 100px;
 }
}
</style>