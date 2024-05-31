
<template>
  <div>
    <Navbar />
  </div>
  <div class="max-w-11xl mx-auto">
    <Body />
  </div>
  <div>
    <Footer />
  </div>
</template>
<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

import Body from "./components/Body.vue";
</script>