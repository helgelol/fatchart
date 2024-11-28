<script lang="ts">
  import { Line } from 'svelte-chartjs';

  // Prepare the data and options for the chart
  const data = {
    labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun'],
    datasets: [
      {
        label: 'Person A',
        backgroundColor: 'rgba(75,192,192,0.2)',
        borderColor: 'rgba(75,192,192,1)',
        data: [65, 59, 80, 81, 56, 55],
        fill: false,
      },
      {
        label: 'Person B',
        backgroundColor: 'rgba(255,99,132,0.2)',
        borderColor: 'rgba(255,99,132,1)',
        data: [28, 48, 40, 19, 86, 27],
        fill: false,
      },
    ],
  };
</script>

<div class="graph-container">
  Start of chart
  <Line {data} />
  End of chart
</div>

<style>
  .graph-container {
    margin: auto;
    width: 100%;
    height: 400px;
  }
</style>
