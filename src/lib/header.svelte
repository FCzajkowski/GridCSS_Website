<script>
    import gridImage from '../assets/GridCSS.svg';

    function redirect(website){
        window.location.href = website;
    }
</script>
<style lang="scss">
    @use "../style";
</style>

<header>
    <img src="{gridImage}" alt="" width="50" height="50">
    <div>
        <button on:click="{redirect("/hello")}">Get Started</button>
        <button on:click="{redirect("https://github.com/FCzajkowski/GridCSS/blob/main/DOCUMENTATION.md")}">Documentation</button>
        <button on:click="{redirect("https://github.com/FCzajkowski/GridCSS/")}">Github</button>
    </div>
</header>