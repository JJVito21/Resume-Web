<script setup>
import { ref } from 'vue'
import Home from '@/pages/Home.vue'
import Navbar from '@/components/Navbar.vue'
import AboutMe from '@/pages/About-Me.vue'
import Education from '@/pages/Education.vue'
import Experience from '@/pages/Experience.vue'
import Socials from '@/pages/Socials.vue'

</script>

<template>
  <div>
    <Navbar />
    <Home />
    <AboutMe />
    <Education />
    <Experience />
    <Socials />
  </div>
</template>



<style scoped></style>