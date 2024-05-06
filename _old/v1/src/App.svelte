<script lang="ts">
  import Hero from './lib/Hero.svelte';
  import Navbar from './lib/Navbar.svelte';
  import Tech from './lib/Tech.svelte';
  import Hr from './lib/Hr.svelte';
  import Projects from './lib/Projects.svelte';
  import Footer from './lib/Footer.svelte';
</script>

<main>
  <Navbar />

  <div id="container">
    <Hero />
    <Hr />

    <Tech />
    <Hr />

    <Projects />
  </div>

  <Footer />
</main>

<style>
  :global(:root) {
    --color-accent: #60B8D3;;
    --color-light-grey: #707070;
  }

  #container {
    width: 70%;
    margin: 0 auto;
  }
</style>
