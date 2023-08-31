<template>
  <div id="nav">
    <Navbar />
<router-view/>
    <Footer></Footer>
  </div>
</template>

<script setup>
import Navbar from '@/components/Navbar.vue';
</script>