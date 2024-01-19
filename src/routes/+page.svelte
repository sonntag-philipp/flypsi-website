<script>
    import Heading from '$lib/heading.svelte';
</script>

<div class="h-dvh w-full overflow-y-scroll snap-mandatory snap-y">
    <div class="slides bg-slate-700">
        <Heading />
    </div>
    <div class="slides bg-red-600">
        <Heading />
    </div>
    <div class="slides bg-blue-600">
        <Heading />
    </div>
</div>

<style lang="postcss">
    .slides {
        @apply flex flex-col items-center justify-center w-full h-dvh gap-4 snap-start;
    }
</style>
