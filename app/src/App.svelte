<script lang="ts">
  import FrontPage from './components/FrontPage.svelte';
  import Graph from './components/Graph.svelte';
</script>

<svelte:head>
  <title>Fatchart 2.0</title>
  <link rel="apple-touch-icon" sizes="180x180" href="./apple-touch-icon.png" />
  <link rel="icon" type="image/png" sizes="32x32" href="./favicon-32x32.png" />
  <link rel="icon" type="image/png" sizes="16x16" href="./favicon-16x16.png" />
  <link rel="manifest" href="./site.webmanifest" />
  <link rel="preconnect" href="https://fonts.gstatic.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Nunito:ital@1&display=swap"
    rel="stylesheet"
  />
  <script src="https://kit.fontawesome.com/929d0d8056.js" crossorigin="anonymous">
  </script>
</svelte:head>
<main>
  <!-- <FrontPage /> -->
  <Graph />
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  body {
    overflow: hidden;
    width: 100%;
    height: 100vh;
    color: #fff;
    /* background: #14171b; */
    position: relative;
    font-family: 'Nunito', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
  }
</style>
