<script lang="ts">
  // import svelteLogo from './assets/svelte.svg';
  // import Counter from './lib/Counter.svelte';

  import Nav from './lib/Nav.svelte';
  import Home from './lib/Home.svelte';
  import About from './lib/AboutMe.svelte';
  import Portfolio from './lib/Portfolio.svelte';
  import Footer from './lib/Footer.svelte';
</script>

<main class="max-w mx-auto px-4">
  <div class="pt-4 pb-12">
    <Nav />
    <Home />
    <About />
    <Portfolio />
    <Footer />
  </div>
</main>
