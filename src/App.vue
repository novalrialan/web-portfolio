
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
</script>