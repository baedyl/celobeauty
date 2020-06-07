<template>
  <img src="~/assets/logo.png" class="NuxtLogo" />
</template>
<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
  width: 150px;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
