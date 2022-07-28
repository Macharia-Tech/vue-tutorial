<template>
<div class="bg-img">
<nav class="container">
  <div class="topnav">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#contact">Contact</a>
  </div>
</nav>
</div>
  
</template>

<style >
.bg-img{
  background-image: url('/home/engineer/Desktop/Kweli Projects/new/Vuenew/public/image1.jpeg');
  min-height: 800px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

  position:relative;

}
.container{
  position: absolute;
  margin: 20px;
  width: auto;
}

.topnav{
  overflow: hidden; 
  background: grey;

}  
.topnav a{
  float: left;
  text-align:center;
  padding: 14px 16px;
  font-size: 20px;
}

.topnav a:hover {
  background-color:  #ddd;
  color: black;
}
</style>
