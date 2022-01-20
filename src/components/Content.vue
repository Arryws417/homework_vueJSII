<template>
  <div>
   <div class="title">
       <h2><span>Experience</span></h2>
   </div>
      <div class="content" style="display: flex; flex-direction: row;justify-content: center; align-items: center;">
            <div class="image-container">
            <img src="img/telkomakses.jpg" width="200px">
       </div>
         <div style="width: 50%; justify-content: center; align-items: center;">
            <h1 style="color: green">My Experience in 2015</h1>
            <h3 style="color: green">PT.Telkom Akses</h3>
            <h4 style="color: green">Jl.Arif Rachman Hakim, Depok</h4>
            <p style="text-align: justify;"><strong>During i'm in the PT.Telkom Akses</strong> i'm doing Fiber Optic Instalation for cust Ftth/x 
               Measurement Fiber Optic Using OPM,OTDR,OLS doing activation new customer and migration cooper cable to fiber optics
            </p>
         <button class="button" onclick="Read()"><span>Read</span></button><br>
         <div style="background-color: grey;text-align: center; padding:10px; margin-top:8px;">
            © copyright Arry Wiandana.S
      </div>
    </div>
    </div>
    </div>
</template>

<script>
export default {}
</script>

<style>

 .title {
    margin: 20px 25%;
 }
 .content {
    margin: 0 25%;
 }
 .content-1 {
     margin: 0 25%;
 }
 .button {
   border-radius: 4px;
   background-color: #f4511e;
   border: none;
   color: #FFFFFF;
   text-align: center;
   font-size: 15px;
   padding: 15px;
   width: 150px;
   transition: all 0.5s;
   cursor: pointer;
   margin: 5px;
 }
 .button span {
   cursor: pointer;
   display: inline-block;
   position: relative;
   transition: 0.5s;
 }
 .button span:after {
   content: '00bb';
   position: absolute;
   opacity: 0;
   top: 0;
   right: -20px;
   transition: 0.5s;
 }
 .button:hover span {
   padding-right: 15px;
 }
 .button:hover span:after {
   opacity: 1;
   right: 0;
 }
</style>
