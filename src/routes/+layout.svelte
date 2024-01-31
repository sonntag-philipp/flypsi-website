<script>
    import '../app.css';
</script>

<svelte:head>
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="manifest" href="/site.webmanifest" />
    <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5" />
    <meta name="msapplication-TileColor" content="#da532c" />
    <meta name="theme-color" content="#ffffff" />

    <meta name="title" content="Philipp Sonntag | Flypsi - Experienced software engineer" />
    <meta
        name="description"
        content="Experienced software engineer located in Oldenburg, Germany with expertise in Angular, .NET, TypeScript, JavaScript, Web Components, etc."
    />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://flyp.si/" />
    <meta property="og:title" content="Philipp Sonntag | Flypsi - Experienced software engineer" />
    <meta
        property="og:description"
        content="Experienced software engineer located in Oldenburg, Germany with expertise in Angular, .NET, TypeScript, JavaScript, Web Components, etc."
    />
    <meta property="og:image" content="https://flyp.si/logo.png" />

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image" />
    <meta property="twitter:url" content="https://flyp.si/" />
    <meta
        property="twitter:title"
        content="Philipp Sonntag | Flypsi - Experienced software engineer"
    />
    <meta
        property="twitter:description"
        content="Experienced software engineer located in Oldenburg, Germany with expertise in Angular, .NET, TypeScript, JavaScript, Web Components, etc."
    />
    <meta property="twitter:image" content="https://flyp.si/logo.png" />
</svelte:head>

<div>
    <slot />
</div>

<style type="postcss">
    div {
        @apply bg-gradient-to-r from-slate-700 via-cyan-900 to-green-700;
        @apply min-h-full;
    }
</style>
