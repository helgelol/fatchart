<script lang="ts">
  import Logo from './Logo.svelte';
  import Brand from './Brand.svelte';
  import Chart from './Chart.svelte';

  import { fade } from 'svelte/transition';
</script>

<div in:fade={{ delay: 500 }}>
  <Logo />
  <Brand />
  <Chart />
</div>
