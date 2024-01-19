<script>
    import Greeting from '$lib/greeting.svelte';
</script>

<div class="h-dvh w-full overflow-y-scroll snap-mandatory snap-y">
    <div class="slides bg-slate-700">
        <Greeting />
    </div>
    <div class="slides bg-blue-700">
        <h1>My Technologies</h1>
    </div>
    <div class="slides bg-teal-700">
        <h1>Projects</h1>
    </div>
    <div class="slides bg-slate-700">
        <h1>Education</h1>
    </div>
    <div class="slides bg-teal-700">
        <h1>Open Source</h1>
    </div>
    <div class="slides bg-blue-700">
        <h1>Contact</h1>
    </div>
</div>

<style lang="postcss">
    h1 {
        @apply text-xl md:text-3xl;
        font-family: monospace;
    }

    .slides {
        @apply flex flex-col items-center justify-center w-full h-dvh gap-4 snap-start;
    }
</style>
