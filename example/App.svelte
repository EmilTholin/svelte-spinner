<script>
  import Spinner from 'svelte-spinner';

  let size = 50;
  let speed = 750;
  let color = '#A82124';
  let thickness = 2.0;
  let gap = 40;
</script>

<h1>Svelte Spinner</h1>
<div>
  <label>Size: {size}px</label>
  <input type="range" min="0" max="100" step="1" bind:value="{size}"/>

  <label>Speed: {speed}ms</label>
  <input type="range" min="50" max="2000" step="10" bind:value="{speed}">

  <label>Color</label>
  <input type="text" bind:value="{color}">

  <label>Thickness: {thickness}</label>
  <input type="range" min="0.1" max="10" step="0.1" bind:value="{thickness}">

  <label>Gap: {gap}%</label>
  <input type="range" min="0" max="100" step="1" bind:value="{gap}">
</div>

<Spinner 
  size="{size}"
  speed="{speed}"
  color="{color}"
  thickness="{thickness}"
  gap="{gap}"
/>
