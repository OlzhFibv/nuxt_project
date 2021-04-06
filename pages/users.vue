<template>
  <div>
    <div class="bg">
    <div class="topnav shadow-md">
      <a href="/">Main</a>
      <a href="/news">News</a>
      <a href="/login">Sign in</a>
      <a class="active" href="#home">About</a>
      <div class="mx-8 absolute inset-y-0 right-0 "><img src="../assets/images/jujutsu.png" class="logotype" alt="image"></div>
    </div>
    <div class="about-section bg-gradient-to-r from-yellow-200 via-yellow-400 to-yellow-500 shadow- inner">
  <p class="text-5xl text-black ">About Us Page</p>
  <p class="text-3xl text-black" >Some info about who we are.</p>

</div>
    <div class="grid grid-cols-3 gap-4 mx-40 my-8">
      <span class="bg-gray-300 rounded-xl mx-12">
    <div v-for="user in users" :key="user.id">
      <div
        class="p-6 max-w-sm mx-auto bg-yellow-200 rounded-xl shadow-md flex items-center space-x-4 m-4"
      >
        <div class="flex-shrink-0">
          <img
            class="h-12 w-12"
            :src="user.avatar"
            alt="ChitChat Logo"
          />
        </div>
        <div>
          <div class="text-xl font-medium text-black">{{ user.first_name }}</div>
          <p class="text-black-500">{{ user.last_name }}</p>
          <p class="text-black-500">{{ user.email}}</p>
          <p class="group hover:text-white transition delay-50 duration-400 text-gray-500">Elders</p>
        </div>
      </div>
    </div>
    </span>
    <span class="bg-gray-300 rounded-xl mx-12">
    <div v-for="user in users" :key="user.id">
      <div
        class="p-6 max-w-sm mx-auto bg-yellow-300 rounded-xl shadow-md flex items-center space-x-4 m-4"
      >
        <div class="flex-shrink-0">
          <img
            class="h-12 w-12"
            :src="user.avatar"
            alt="ChitChat Logo"
          />
        </div>
        <div>
          <div class="text-xl font-medium text-black">{{ user.first_name }}</div>
          <p class="text-black-500">{{ user.last_name }}</p>
          <p class="text-black-500">{{ user.email}}</p>
          <p class="group hover:text-white transition delay-50 duration-400 text-gray-500">Moderators</p>
        </div>
      </div>
    </div>
    </span>
    <span class="bg-gray-300 rounded-xl mx-12">
    <div v-for="user in users" :key="user.id">
      <div
        class="p-6 max-w-sm mx-auto bg-yellow-400 rounded-xl shadow-md flex items-center space-x-4 m-4"
      >
        <div class="flex-shrink-0">
          <img
            class="h-12 w-12"
            :src="user.avatar"
            alt="ChitChat Logo"
          />
        </div>
        <div>
          <div class="text-xl font-medium text-black">{{ user.first_name }}</div>
          <p class="text-black-500">{{ user.last_name }}</p>
          <p class="text-black-500">{{ user.email}}</p>
          <p class="group hover:text-white transition delay-50 duration-400 text-gray-500">Editors</p>
        </div>
      </div>
    </div>
    </span>
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
  
  </div>
</template>
<style scoped>
.logotype{
  width: 150px;

}
.about-section {
  padding: 50px;
  text-align: center;
  background-color: #ffd900;
  color: white;
}
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
  background-color: #ffd900;
  color: rgb(0, 0, 0);
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #ffd900;
  color: rgb(0, 0, 0);
}


.bg{
  background-color: rgb(27, 27, 27);
}

.footer-links {
    padding-bottom: 2px;
  
}
</style>
<script>

import axios from "axios";
export default {
  data() {
    return {
      users: [],
    };
  },
  async mounted() {
    const { status, data } = await axios.get("https://reqres.in/api/users?page=1");
    this.users = data.data;
  },
};
</script>
