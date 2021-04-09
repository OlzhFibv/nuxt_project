<template class="bg-clr">

<div >
  
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Karma">
<header class="video-header">
  <video src="../assets/videos/kaisen.mp4" autoplay loop playsinline muted></video>
  <div class="viewport-header">
<div class="w3-black w3-sidebar w3-bar-block w3-collapse w3-card w3-display-left" style="width:200px;" id="mySidebar">
  <button class="w3-bar-item w3-button w3-hide-large"
  onclick="w3_close()">Close &times;</button>
  <div class="w3-center w3-padding-32 w3-yellow w3-bottombar w3-border-darkgray" style="font-family: Arial">Catalogue</div>
  <a href="#" class="w3-black w3-bar-item w3-button w3-border-bottom w3-border-darkgray">Popular</a>
  <a href="#" class="w3-black w3-bar-item w3-button w3-border-bottom w3-border-darkgray">Filter</a>
  <a href="#" class="w3-black w3-bar-item w3-button w3-border-bottom w3-border-darkgray">Random Manga</a>
  <a href="#" class="w3-black w3-bar-item w3-button w3-border-bottom w3-border-darkgray">Manhua</a>
  <a href="#" class="w3-black w3-bar-item w3-button w3-border-bottom w3-border-darkgray">Classics</a>
</div>
<!-- Top menu -->
<div class="w3-main" style="margin-left:200px">
<div class=" w3-top w3-border w3-border-black ">
  <div class=" w3-xlarge" style="max-width:auto;margin:auto">
    <NuxtLink to="/" class="w3-button w3-padding-16 w3-yellow w3-left w3-hover-black">Main</NuxtLink>
    <NuxtLink to="/login" class="w3-button w3-padding-16 w3-yellow w3-left w3-hover-black">Sign in</NuxtLink>
    <NuxtLink to="/users" class="w3-button w3-padding-16 w3-yellow w3-left w3-hover-black">About</NuxtLink>
    <div class="w3-center w3-yellow w3-padding-16 ">Manga catalogue: Popular</div>
  </div>
</div>
  </div>

<!-- !PAGE CONTENT! -->
<div class="w3-main w3-content w3-padding" style="max-width:1200px;margin-top:100px">

  <!-- First Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center " id="food">
    <div class=" w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/ch-man.jpg" alt="Sandwich" style="width:80% " class="w3-margin">
      <h3>Chainsaw-man <span class="w3-badge w3-green">9</span></h3>
    </div>
    <div class="w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/kaiju.jpg" alt="Steak" style="width:90%" class="w3-margin">
      <h3>Kaiju-8 <span class="w3-badge w3-green">8</span></h3>
    </div>
    <div class="w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/yaiba.jpg" alt="Cherries" style="width:80%" class="w3-margin"> 
      <h3>Demon slayer <span class="w3-badge w3-green">8.3</span></h3>
    </div>
    <div class="w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/desunoto.jpg" alt="Pasta and Wine" style="width:85%" class="w3-margin">
      <h3>Deatn Note <span class="w3-badge w3-green">9.2</span></h3>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center" >
    <div class="w3-card-4 w3-quarter w3-text-white  w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/kaisen.jpg" alt="Popsicle" style="width:80%" class="w3-margin">
      <h3>Jujutsu Kaisen <span class="w3-badge w3-green">8.5</span></h3>
    </div>
    <div class="w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/kaguya.jpg" alt="Salmon" style="width:80%" class="w3-margin">
      <h3>Love war:Kaguya-sama <span class="w3-badge w3-green">8.5</span></h3>
    </div>
    <div class="w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/neverland.jpg" alt="Sandwich" style="width:80%" class="w3-margin"> 
      <h3>Promised Neverland <span class="w3-badge w3-green">7.9</span></h3>
    </div>
    <div class="w3-card-4 w3-quarter w3-text-white w3-hover-yellow w3-margin-left w3-margin-right" style="width:180px">
      <img src="../assets/images/shobotai.jpg" alt="Croissant" style="width:80%" class="w3-margin">
      <h3>Enen no Shouboutai <span class="w3-badge w3-green">8.0</span></h3>
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-8 ">
    <div class="w3-bar w3-text-yellow ">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>
  <!-- Footer --> 
<!-- End page content -->
</div>
  </div>
</header>
</div>
</template>

<style scoped>
.bg-clr{
  background:black ;
}
.video-header {
  position:absolute;
  text-align: center;
  width: 100vw;
  height: 100vh;
}
.video-header, .video-header video, .video-header .viewport-header {
  width: 100vw;
  height: 100vh;
  position: absolute;
  top: 0;
  left: 0;
}
.video-header video {
  background: brown;
  object-fit: cover;
}
.video-header, .viewport-header {
  display: flex;
  align-items: center;
  justify-content: center;
}
body,h1,h2,h3,h4,h5,h6 {font-family: "Ariel", sans-serif}
.w3-bar-block .w3-bar-item {padding:50px}
</style>
<script>
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
}

function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>


