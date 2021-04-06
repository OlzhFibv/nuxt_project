<template>
<div>
    <main>
      <img class="NuxtLogo" src="../assets/images/jujutsu.png" alt="logo" width="400" >
      <Nuxt />
    </main>
  </div>

</template>

<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
  -webkit-animation: pulsing 10s infinite;
  animation: pulsing 10s infinite;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
@keyframes pulsing {
  0% {
    -webkit-transform: scale(0.8, 0.8);
    transform: scale(0.8, 0.8)
  }
  50% {
    -webkit-transform: scale(1.0, 1.0);
    transform: scale(1.0, 1.0);
  }
  100% {
    -webkit-transform: scale(0.8, 0.8);
    transform: scale(0.8, 0.8);
  }
}
@-webkit-keyframes pulsing {
  0% {
    -webkit-transform: scale(0.8, 0.8);
    transform: scale(0.8, 0.8)
  }
  50% {
    -webkit-transform: scale(1.0, 1.0);
    transform: scale(1.0, 1.0);
  }
  100% {
    -webkit-transform: scale(0.8, 0.8);
    transform: scale(0.8, 0.8);
  }
}

</style>
