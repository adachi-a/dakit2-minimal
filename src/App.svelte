<script>
  import Search from './Search.svelte';
  import './app.scss';
  import * as bootstrap from 'bootstrap';
</script>

<svelte:head>
  <meta name="robots" content="noindex, nofollow" />
</svelte:head>

<header class="navbar bg-primary navbar-expand-md">
  <nav class="container-md flex-wrap flex-md-nowrap" aria-label="Main navigation">
    <!-- svelte-ignore a11y-invalid-attribute -->
    <a class="navbar-brand p-0 me-4" href="#"><span>DAKit Test Site</span></a>
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav ms-auto" />
    </div>
  </nav>
</header>

<div class="container">
  <Search />
</div>
