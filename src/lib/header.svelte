<script>
    import gridImage from '../assets/GridCSS.svg';
    import { redirect } from './utils.js';

</script>
<style lang="scss">
    @use "../style";
</style>

<header>
    <img src="{gridImage}" alt="" width="50" height="50">
    <div>

        <button on:click="{redirect("#/GetStarted")}">Get Started</button>
        <button on:click="{redirect("https://github.com/FCzajkowski/GridCSS/blob/main/DOCUMENTATION.md")}">Documentation</button>
        <button on:click="{redirect("https://github.com/FCzajkowski/GridCSS/")}">Github</button>
    </div>
</header>