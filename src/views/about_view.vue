<template>
  <div class="about">
    <Navbar />
      <div>
  <About />
  <Footer />
</div>
</div>
</template>

<script>
     import Navbar from "../components/navbar.vue";
     import About from "../components/about.vue";
     import Footer from "../components/footer.vue";
  export default {
      name: 'about',
      components: {Navbar,About,Footer},
  };
</script>