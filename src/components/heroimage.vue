<template>
    <div class="hero-image">
        <div class="hero-text">
            <h1>Hello I'am Arry Wiandana Syahputra</h1>
            <p>I'm a Engineer & Developers</p>
            <p>Telecomunication Network | Fullstack DevSec | AI Enthusiast</p>
            <button>Hire me</button>
          </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>

 /* The hero image */
 .hero-image {
   /* Use "linear-gradient" to add a darken background effect to the image (photographer.jpg). This will make the text easier to read */
   background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("../assets/fullstack.jpg");
   height: 60vh;
 
   background-position: center;
   background-repeat: no-repeat;
   background-size: cover;
   position: relative;
 }
 .hero {
    position: overlay;
 }
 .hero-text {
   text-align: center;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%, -50%);
   color: white;
 }
 .hero-text h1:hover{
    color: red;
    transition: 0.4s;
    cursor: pointer;
 }
 .hero-text p:hover {
    color: red;
    transition: 0.3s;
    cursor: pointer; 
 }
</style>