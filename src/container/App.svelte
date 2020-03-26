<script>
  import Header from "../components/Header.svelte";
  import Analytics from "../components/Analytics.svelte";
</script>

<style>
  :global(body) {
    background-color: #e3e5e5;
    margin: 0;
    padding: 0;
  }
  :global(h1, h2, h3) {
    margin: 0;
    padding: 0;
  }
</style>

<main>
  <Header />
  <Analytics />
</main>
