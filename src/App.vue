<template>
  <div>
    <Navbar />
    <Hero />
    <About />
    <Project />
    <Services />
    <Contact />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "./views/HomeView.vue";
import About from "./views/AboutView.vue";
import Project from "./views/ProjectView.vue";
import Services from "./views/ServicesView.vue";
import Contact from "./views/ContactView.vue";
import Footer from "./components/Footer.vue";
</script>
