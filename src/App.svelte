<script lang="ts">
  import svelteLogo from './assets/profile_picture.png'
</script>

<main>
  <div>
    <a href="https://svelte.dev" target="_blank"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Flyp.si</h1>

  <div class="card">
    Hallo :)
  </div>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>

<style>
  .logo {
    border-radius: 50%;
    height: 20rem;
    padding: 1.5em;
    will-change: filter;
  }
</style>