<script>
  import Router from 'svelte-spa-router';
  import Home from './routes/Home.svelte';
  import GetStarted from './routes/Get-Stared.svelte';

  const routes = {
    '/': Home,
    '/GetStarted': GetStarted
  };
</script>

<Router {routes} />