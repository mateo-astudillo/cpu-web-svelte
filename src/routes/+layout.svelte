<script>
  import '../app.css';
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';
</script>

<Header />

<main>
  <slot />
</main>

<Footer />

<style>
  main {
    flex-grow: 2;
    display: flex;
    justify-content: center;
  }
</style>
