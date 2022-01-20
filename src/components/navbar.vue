<template>
    <div class="topnav" id="myTopnav">
      <a href="#home" class="active">Home</a>
      <a href="project.html">Projects</a>
      <a href="labs.html">Labs</a>
      <a href="about.html">About</a>
      <a href="javascript:void(0);" class="icon" onclick="myFunction()">
        <i class="fa fa-bars"></i>
      </a>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
.topnav {
     background-color: #333;
     overflow: hidden;
 }
   body {
       margin: 0;
       padding: 0;
    }
    .topnav a {
     float: left;
     display: block;
     color: #f2f2f2;
     text-align: center;
     padding: 14px 16px;
     text-decoration: none;
     font-size: 17px;
     transition: .5s;
 }
    .topnav a:hover {
    background-color: #ddd;
    color: red;
 }
 .topnav a.active{
    background-color: #ddd;
    color: red;
 }
 .topnav .icon{
    display: none;
 }
</style>