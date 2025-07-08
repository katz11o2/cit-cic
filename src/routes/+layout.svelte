<script>
  import Header from '../components/Header.svelte';
  import Footer from '../components/Footer.svelte';
</script>

<div class="app-wrapper">
  <Header />

  <main class="main-content">
    <slot />
  </main>

  <Footer />
</div>

<style>
  .app-wrapper {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    width: 100%;
  }

  .main-content {
    flex-grow: 1;
  }
</style>
