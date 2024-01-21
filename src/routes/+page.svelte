<script>
    import Greeting from '$lib/greeting.svelte';
    import Technologies from '$lib/technologies.svelte';
</script>

<div class="h-dvh w-full overflow-y-scroll snap-mandatory snap-y">
    <div class="slides">
        <Greeting />
    </div>
    <div class="slides">
        <Technologies />
    </div>
    <div class="slides bg-teal-700">
        <h1 class="text-white">Projects</h1>
    </div>
    <div class="slides bg-teal-700">
        <h1 class="text-white">Education</h1>
    </div>
    <div class="slides bg-slate-700">
        <h1 class="text-white">Open Source</h1>
    </div>
    <div class="slides bg-amber-700">
        <h1 class="text-white">Contact</h1>
    </div>
</div>

<style lang="postcss">
    h1 {
        @apply text-xl md:text-3xl;
        font-family: monospace;
    }

    .slides {
        @apply bg-gradient-to-r from-slate-700 via-cyan-900 to-green-700;
        @apply flex flex-col items-center justify-center w-full h-dvh gap-4 snap-start;
    }
</style>
