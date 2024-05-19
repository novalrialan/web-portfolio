
<template>
  <div>
    <Navbar />
  </div>
  <div class="max-w-11xl mx-auto">
    <Container />
  </div>
  <div class="max-w-11xl mx-auto">
    <ContainerBody />
  </div>
  <div>
    <Footer />
  </div>
</template>
<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

import Container from "./components/Container.vue";
import ContainerBody from "./components/ContainerBody.vue";

// // On page load or when changing themes, best to add inline in `head` to avoid FOUC
// if (
//   localStorage.getItem("color-theme") === "dark" ||
//   (!("color-theme" in localStorage) &&
//     window.matchMedia("(prefers-color-scheme: dark)").matches)
// ) {
//   document.documentElement.classList.add("dark");
// } else {
//   document.documentElement.classList.remove("dark");
// }
</script>