<div class="h-full w-full flex flex-col">
    <div class="w-full grow flex flex-col pb-16 justify-center items-center">
        <div class="grow flex flex-col gap-4 pb-4 justify-center items-center">
            <enhanced:img
                class="rounded-full max-h-xs h-60 max-w-xs w-60 shadow-2xl aspect-square"
                alt="The developers with green leaves in the background"
                src="$lib/assets/images/profile_picture.jpg"
            />
            <h1 class="title">Hey there! I'm Philipp,</h1>
            <h2 class="subtitle">but feel free to call me Flypsi!</h2>
        </div>
        <div class="flex justify-center">
            <a class="hover:underline underline-offset-2" href="mailto:contact@flyp.si"
                >Contact me</a
            >
        </div>
    </div>
    <div class="w-full flex items-end justify-end gap-1">
        <p class="select-none">Scroll for more</p>
        <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6 animate-bounce"
        >
            <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M19.5 13.5 12 21m0 0-7.5-7.5M12 21V3"
            />
        </svg>
    </div>
</div>

<style type="postcss">
    .subtitle {
        @apply text-base md:text-xl text-slate-950 opacity-0;
        animation: fadeIn 0.5s ease-in-out 3s forwards;
    }

    .title {
        @apply text-white text-xl md:text-3xl;

        overflow: hidden; /* Ensures the content is not revealed until the animation */
        border-right: 0.15em solid orange; /* The typwriter cursor */
        white-space: nowrap; /* Keeps the content on a single line */
        margin: 0 auto; /* Gives that scrolling effect as the typing happens */
        letter-spacing: 0.15em; /* Adjust as needed */
        animation:
            typing 3s steps(30, end),
            blink-caret 1s step-end infinite;
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
