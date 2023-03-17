<script>
  import Navbar from "./lib/Navbar.svelte";
  import About from "./lib/About.svelte";
  import Benefits from "./lib/Benefits.svelte";
  import Footer from "./lib/Footer.svelte";
</script>

<main>
  <Navbar />
  <div class="about"><About /></div>
  <div class="benefits"><Benefits /></div>
  <div class="footer"><Footer /></div>
</main>

<style>
  main {
    padding: 2rem;
    padding-top: 0;
  }
  .about, .benefits, .footer {
    margin-top: 80px;
  }
</style>