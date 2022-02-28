<script>
    import Tony from '../images/tony.svelte'
</script>
<main>
<h1>Coming Soon</h1>

<h2 class='head'>
<Tony />
</h2>
</main>
<style>
    main {
        display: flex;
        flex-direction: column;
        align-items: center;
        font-size: 1rem;
        margin-top: 10px;
        text-align: center;
        width: 100vw;
    }

    @media (min-width: 1280px) {
        main {
            font-size: 3rem;
        }
    }

    .head {
        min-height: 30vh;
        max-height: 75vh;
        min-width: 50vw;
        max-width: 80vw;
    }
    @media (min-width: 1280px) {
        .head {
            min-width: 10vw;
        }
    }
</style>