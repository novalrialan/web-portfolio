<script setup>
// import GreetingMessage  from '@/components/GreetingMessage.vue';
import Navbar        from './assets/Navbar.vue';
import Container     from './assets/Container.vue';
import ContainerBody from './assets/Container-body.vue';
</script>

<template>
  <div class="max-w-10xl mx-auto">
    <Navbar/>
  </div>
  <div class="max-w-11xl mx-auto">
    <Container/>
  </div>
  <div class="bg-indigo-950 h-70" >
    <ContainerBody/>
  </div>



  
</template>
