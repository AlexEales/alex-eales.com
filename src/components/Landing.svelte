<div class="flex flex-col items-center justify-center h-screen">
    <div class="container">
        <h1 class="type-out font-black text-9xl">
            Alex Eales
        </h1>
        <p class="text-xl">
            Backend Engineer
        </p>
    </div>
</div>

<style>
    @keyframes typing {
        0% {
            padding-right: 0;
            width: 0;
        }
        15% {
            padding-right: 0.1em;
            width: 100%;
        }
        85% {
            padding-right: 0.1em;
            width: 100%;
        }
        100% {
            padding-right: 0;
            width: 0;
        }
    }

    .container {
        width: fit-content;
    }

    .type-out {
        animation: typing 8s alternate infinite;
        border-right: .15em solid;
        overflow: hidden;
        padding-right: 0.1em;
        white-space: nowrap;
        width: 0;
    }
</style>
