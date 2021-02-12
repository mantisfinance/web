<template>
  <div id="app" class="text-gray-900 flex flex-col min-h-screen">
    <!-- <Header></Header> -->
    <div class="flex-shrink-0 py-12 text-center">
      <Hero></Hero>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import Hero from 'Components/Hero.vue';
// import Header from 'Components/Header.vue';
import Footer from 'Components/Footer.vue';

export default {
  name: 'App',
  components: {
    // Header,
    Hero,
    Footer,
  },
  data() {
    return {
      message: 'Source on GitHub'
    };
  },
};
</script>

<style>
  @import './styles/style.css';
</style>
