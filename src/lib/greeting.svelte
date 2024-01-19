<script>
    import profile_picture from '$lib/assets/images/profile_picture.jpg';
    import github_logo from '$lib/assets/images/github-logo.svg';
</script>

<div class="flex flex-col h-full">
    <div class="grow flex flex-col gap-4 p-4 justify-center items-center">
        <img
            class="rounded-full max-h-xs h-60 max-w-xs w-60 shadow-2xl aspect-square"
            alt="The developers with green leaves in the background"
            src={profile_picture}
        />
        <h1 class="title">Hey there! I'm Philipp,</h1>
        <h2 class="subtitle">but feel free to call me Flypsi!</h2>
    </div>
    <div class="p-4 flex justify-center">
        <img
            class="rounded-full max-h-xs h-14 max-w-xs w-h-14 shadow-sm aspect-square"
            alt="GitHub logo"
            src={github_logo}
        />
    </div>
</div>

<style>
    .subtitle {
        @apply text-base md:text-xl text-slate-950 opacity-0;
        font-family: monospace;
        animation: fadeIn 0.5s ease-in-out 3s forwards;
    }

    .title {
        @apply text-white text-xl md:text-3xl;
        font-family: monospace;
        overflow: hidden; /* Ensures the content is not revealed until the animation */
        border-right: 0.15em solid orange; /* The typwriter cursor */
        white-space: nowrap; /* Keeps the content on a single line */
        margin: 0 auto; /* Gives that scrolling effect as the typing happens */
        letter-spacing: 0.15em; /* Adjust as needed */
        animation:
            typing 3s steps(30, end),
            blink-caret 0.5s step-end infinite;
    }

    @keyframes fadeIn {
        from {
            opacity: 0;
        }
        to {
            opacity: 1;
        }
    }

    /* The typing effect */
    @keyframes typing {
        from {
            width: 0;
        }
        to {
            width: 100%;
        }
    }

    /* The typewriter cursor effect */
    @keyframes blink-caret {
        from,
        to {
            border-color: transparent;
        }
        50% {
            border-color: orange;
        }
    }
</style>
