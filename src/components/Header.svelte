<script>
  import Hero from "./Hero.svelte";
</script>

<style>
  .Header {
    background-color: #2473e7;
    color: white;
    padding: 1em 0;
  }
  .Header-container {
    display: grid;
    grid-template-columns: minmax(auto, 1024px);
    justify-content: center;
    align-items: center;
  }
  .Header-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .Header-nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  .Header-nav li {
    display: inline-block;
    margin: 0 0 0 0.5em;
  }
  .Header-nav li:nth-child(1) {
    color: rgba(255, 255, 255, 0.7);
  }
</style>

<div class="Header">
  <div class="Header-container">
    <div class="Header-content">
      <div class="Header-title">Firebase Project</div>
      <div class="Header-nav">
        <ul>
          <li>Ir a la documentación</li>
          <li>Campanita</li>
          <li>Avatar</li>
        </ul>
      </div>
    </div>
    <Hero />
  </div>
</div>
