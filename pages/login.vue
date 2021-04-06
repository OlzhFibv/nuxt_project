<template>
<div>
  <div class="bg-color">
    <div class="topnav">
      <a href="/">Home</a>
      <a href="/news">News</a>
<a class="active" href="#home">Sign in</a>
      <a href="/users">About</a>
      <input type="text" placeholder="Search.." name="search" />
    </div>
      <div class="container">
          <form @submit.prevent>
              <h1 class="title">
          sign in
        </h1>
          <label for="username">Username</label>
          <input v-model="user.username" id="username" type="text" />
          <label for="password">Password</label>
          <input v-model="user.password" id="password" type="text" />
          <NuxtLink to="/profile" class="button">Login</NuxtLink>
          <NuxtLink to="/" class="button">Main</NuxtLink>
          </form>
      </div>
  </div>
</div>

</template>
<script>
// Get the video
var video = document.getElementById("myVideo");

// Get the button
var btn = document.getElementById("myBtn");

// Pause and play the video, and change the button text
function myFunction() {
  if (video.paused) {
    video.play();
    btn.innerHTML = "Pause";
  } else {
    video.pause();
    btn.innerHTML = "Play";
  }
}
export default {
  layout: 'auth',
  data() {
    return {
      user: {
        username: '',
        password: ''
      }
    }
  }
}
</script>
<style scoped>
div {
  justify-content: center;
  align-items: center;
}

form {
  display: flex;
  flex-direction: column;
}

label {
  font-size: 14px;
  margin: 0 0.5rem;
  margin-bottom: 0.25rem;
}

input {
    background: var(--primary-color);
  font-size: 16px;
  padding: 0.75rem 1rem;
  margin: 0 0.5rem;
  margin-bottom: 0.5rem;
  border: 1px solid #ffffff;
  border-radius: 0.5rem;
  box-shadow: none;
  box-sizing: border-box;
}
.bg-color{
  background-image: url(assets/images/city.jpg);
}

.button {
  margin-top: 0.5rem;
}

.button[disabled] {
  cursor: default;
  opacity: 0.5;
  cursor: not-allowed;
}
.button {
  background: var(--primary-color);
  padding: 0.75rem 1.5rem;
  outline: none;
  border-radius: 0.5rem;
  font-size: 1rem;
  border: 1px solid;
  cursor: pointer;
  color: rgb(255, 255, 255);
  font-weight: 500;
  text-transform: uppercase;
  box-shadow: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06);
  letter-spacing: 0.5px;
  margin: 1rem;
}

button:hover {
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1),
    0 2px 4px -1px rgba(15, 19, 255, 0.06);
  opacity: 1;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
