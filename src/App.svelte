<script lang="ts">
  import profilePicture from './assets/profile_picture.png'
</script>

<main class="w-full h-full flex justify-center">
  <div class="w-full xl:w-4/12 flex justify-evenly flex-col items-center">
    <div class="flex items-center flex-col text-center">
      <img src={profilePicture} class="rounded-full h-64 w-64 aspect-square overflow-hidden" alt="Svelte Logo" />
      <h1 class="mt-4">Hello there 👋</h1>
      <h1 class="mt-4">I'm <span class="italic">Philipp Sonntag</span>, a software developer for many things.</h1>
      <h1 class="mt-4">
        -
      </h1>
      <h1 class="mt-4">
        Currently focused on <i>.NET, TypeScript / JavaScript, Angular</i> and <i>Web Components</i>.
      </h1>
    </div>
    <div class="flex flex-col md:flex-row w-full justify-evenly items-center mb-14">
      <a href="https://github.com/sonntag-philipp">GitHub</a>
      <a href="https://stackoverflow.com/users/11581799">StackOverflow</a>
      <a href="https://open.spotify.com/playlist/7kTZKAN5U7uyDPwVOm1Ec4?si=275e733f72b046d4">日本</a>
    </div>
  </div>
</main>

<style>
  a {
    @apply underline my-2;
  }
</style>