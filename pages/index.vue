
<template>
<div>
  <div class="bg-img">
    <div class="topnav">
      <a class="active" href="#home">Home</a>
      <a href="/news">News</a>
      <a href="/login">Sign in</a>
      <a href="/users">About</a>
       <div class="mx-8 absolute inset-y-0 right-0 "><img src="../assets/images/jujutsu.png" class="logotype" alt="image"></div>
    </div>
    <div class="container1">
      <div>
        <Logo />
        <h1 class="title">Welcome.</h1>
        <h1 class="subtitle">The easiest way to read the manga online.</h1>
        <NuxtLink to="/login" class="button--geron">Sign up</NuxtLink>
      </div>
    </div>
    <div class="row">
  <div class="column">
    <div class="card">
      <p><i class="fa fa-user"></i></p>
      <h3>11+</h3>
      <p>Partners</p>
    </div><br>
  </div>

  <div class="column">
    <div class="card">
      <p><i class="fa fa-check"></i></p>
      <h3>55+</h3>
      <p>Projects</p>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <p><i class="fa fa-smile-o"></i></p>
      <h3>100+</h3>
      <p>Happy Clients</p>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <p><i class="fa fa-coffee"></i></p>
      <h3>100+</h3>
      <p>Meetings</p>
    </div>
  </div>
</div>
  </div>
<footer class="footer-1 bg-gray-700 py-8 sm:py-12 shadow-inner">
  <div class="container mx-auto px-4">
    <div class="sm:flex sm:flex-wrap sm:-mx-4 md:py-4">
    
      <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 sm:mt-0">
        <h5 class="text-xl text-white font-bold mb-6">Resources</h5>
        <ul class="list-none footer-links">
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Resource</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Resource name</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Another resource</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Final resource</a>
          </li>
        </ul>
      </div>
      <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 md:mt-0">
        <h5 class="text-xl font-bold mb-6 text-white">About</h5>
        <ul class="list-none footer-links">
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Team</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Locations</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Privacy</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Terms</a>
          </li>
        </ul>
      </div>
      <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 md:mt-0">
        <h5 class="text-xl font-bold mb-6 text-white">Help</h5>
        <ul class="list-none footer-links">
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Support</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Help Center</a>
          </li>
          <li class="mb-2">
            <a href="#" class="border-b border-solid border-transparent hover:border-yellow-300 hover:text-yellow-300 text-white">Contact Us</a>
          </li>
        </ul>
      </div>
      <div class="px-4 mt-4 sm:w-1/3 xl:w-1/6 sm:mx-auto xl:mt-0 xl:ml-auto">
        <h5 class="text-xl font-bold mb-6 sm:text-center xl:text-left text-white">Stay connected</h5>
        <div class="flex sm:justify-center xl:justify-start">
          <a href="" class="w-8 h-8 border border-2 border-gray-400 rounded-full text-center py-1 text-gray-600 hover:text-white hover:bg-blue-600 hover:border-blue-600">
            <i class="fab fa-facebook"></i>
          </a>
          <a href="" class="w-8 h-8 border border-2 border-gray-400 rounded-full text-center py-1 ml-2 text-gray-600 hover:text-white hover:bg-blue-400 hover:border-blue-400">
            <i class="fab fa-twitter"></i>
          </a>
          <a href="" class="w-8 h-8 border border-2 border-gray-400 rounded-full text-center py-1 ml-2 text-gray-600 hover:text-white hover:bg-red-600 hover:border-red-600">
            <i class="fab fa-google-plus-g"></i>
          </a>
        </div>
      </div>
    </div>

    <div class="container mx-auto px-6">
        <div class="mt-16 border-t-2 border-white flex flex-col items-center">
            <div class="sm:w-2/3 text-center py-6">
                <p class="text-sm text-white font-bold mb-2">
                    © 2020 by Ashimov Olzhas
                </p>
            </div>
        </div>
    </div>
  </div>
</footer>

</div>

</template>

<script>
export default {};
</script>

<style>
.logotype{
  width: 150px;

}
.footer {
  padding: 100px;
  text-align: center;
  background: rgb(68, 68, 68);
}
* {
  box-sizing: border-box;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 5px;
}

.row {margin: 0 -5px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive columns */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 10px;
  }
}

/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  background-color: #444;
  color: white;
}

.fa {font-size:50px;}
.topnav {
 top: 0;
  position: -webkit-sticky;
  position: sticky;
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
.bg-img {
  background-image: url(assets/images/city.jpg);
  margin-left: auto;
  margin-right: auto;
}

.container1 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #ffd900;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #ffffff;
  word-spacing: 5px;
  padding-bottom: 50px;
}

.links {
  margin-top: 1px;
}

.topnav input[type="text"] {
  float: right;
  padding: 6px;
  border: 1px solid yellow;
  margin-top: 8px;
  margin-right: 16px;
  font-size: 17px;
}
@media screen and (max-width: 600px) {
  .topnav a,
  .topnav input[type="text"] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type="text"] {
    border: 1px solid rgb(238, 255, 0);
  }
}

</style>
