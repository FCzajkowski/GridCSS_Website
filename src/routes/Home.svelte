<script>
    import Header from '../lib/header.svelte';
    import { redirect } from '../lib/utils.js';
    const LINK = '<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/FCzajkowski/GridCSS/grid.css">';
</script>

<style lang="scss">
    @use "../style";
</style>

<section class="website">

    <Header />

    <section id="hero_section">
        <h1>
            Minimalistic Layout Framework
        </h1>
        <code>
            {LINK}
        </code>
        <div class="buttons">
            <button on:click={redirect("#/GetStarted")}>Get Started</button>
            <button on:click={redirect("https://github.com/FCzajkowski/GridCSS")}>View on Github</button>
        </div>
    </section>

        
</section>