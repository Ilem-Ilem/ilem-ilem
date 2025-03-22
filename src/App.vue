<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Navigation from './components/Navigation.vue';
import Heros from './components/Heros.vue';
import Skills from './components/Skills.vue';
import Resume from './components/Resume.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue'
import About from './components/About.vue';
  /**
   * Preloader
   */
   const preloader = document.querySelector('#preloader');
  if (preloader) {
    window.addEventListener('load', () => {
      preloader.remove();
    });
  }
 /**
   * Scroll top button
   */
  let scrollTop = document.querySelector('.scroll-top');

  function toggleScrollTop() {
    if (scrollTop) {
      window.scrollY > 100 ? scrollTop.classList.add('active') : scrollTop.classList.remove('active');
    }
  }
 
  document.getElementById('scroll-top')?.addEventListener('click', (e) => {
    e.preventDefault();
    window.scrollTo({
      top: 0,
      behavior: 'smooth'
    });
  });

  window.addEventListener('load', toggleScrollTop);
  document.addEventListener('scroll', toggleScrollTop);
</script>

<template>
  <div id="page" class="s-pagewrap">

    <Navigation />
    <!-- <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav> -->


    <main class="">
      <!-- <RouterView /> -->

      <Heros />

      <!-- About Section -->
      <About />

      <!-- Skills Section -->
      <Skills />
      <!-- Resume Section -->
      <Resume />


      <Contact />
    </main>

   <Footer />
    

  </div>
</template>

<style scoped>



</style>
