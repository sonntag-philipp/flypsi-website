<script>
    import Greeting from '$lib/greeting.svelte';
    import Introduction from '$lib/introduction.svelte';
    import Technologies from '$lib/technologies.svelte';
</script>

<div class="h-dvh w-full overflow-y-scroll snap-mandatory snap-y">
    <div class="slides">
        <Greeting />
    </div>
    <div class="slides">
        <Introduction />
    </div>
    <div class="slides">
        <Technologies />
    </div>
</div>

<style lang="postcss">
    .slides {
        @apply bg-gradient-to-r from-slate-700 via-cyan-900 to-green-700;
        @apply w-full h-dvh snap-start p-6 sm:p-12;
        @apply flex flex-col justify-center items-center;
    }
</style>
