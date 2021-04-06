<template>
<div>
  <div class="topnav">
      <a class="active" href="#home">Home</a>
      <a href="/news">News</a>
      <a href="/login">Sign in</a>
      <a href="/users">About</a>
      <input type="text" placeholder="Search.." name="search" />
    </div>
  <div class="bg-img">
<div class="container">
<video autoplay muted loop id="myVideo">
  <source src="../assets/videos/kimetsu.mp4" type="video/mp4">
</video>
<!-- Optional: some overlay text to describe the video -->
<div class="content">
  <h1>Welcome to the news topic</h1>
  <p>You can also watch anime online at the bruh.anim</p>
</div>
</div>
</div>
</div>
</template>

<style scoped>
.topnav {
  background-color: #333;
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 20px 20px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
  background-color: rgb(255, 218, 96);
  color: rgb(0, 0, 0);
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #ffe815;
  color: rgb(0, 0, 0);
}
body {
  margin: 0;
  font-family: Arial;
  font-size: 17px;
}
/* Style the video: 100% width and height to cover the entire window */
#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
}

/* Add some content at the bottom of the video/page */
.content {
  position: fixed;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}


</style>
<script>

</script>

