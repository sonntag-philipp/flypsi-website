<div class="gap-2 flex flex-col">
    <h1 class="typewriter text-3xl text-white">Hey there! I'm Philipp,</h1>
    <h2 class="subtitle text-2xl text-slate-950">but feel free to call me Flypsi!</h2>
</div>

<style>
    .subtitle {
        font-family: monospace;
        opacity: 0;
        animation: fadeIn 0.5s ease-in-out 3.5s forwards;
    }

    /* DEMO-SPECIFIC STYLES */
    .typewriter {
        color: #fff;
        font-family: monospace;
        overflow: hidden; /* Ensures the content is not revealed until the animation */
        border-right: 0.15em solid orange; /* The typwriter cursor */
        white-space: nowrap; /* Keeps the content on a single line */
        margin: 0 auto; /* Gives that scrolling effect as the typing happens */
        letter-spacing: 0.15em; /* Adjust as needed */
        animation:
            typing 3.5s steps(30, end),
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
