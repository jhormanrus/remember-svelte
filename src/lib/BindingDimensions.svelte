<script>
  let textSize = 10
  let width
  let height
</script>

<input type="range" bind:value={textSize}>

width: {width} height: {height}
<div bind:clientWidth={width} bind:clientHeight={height}>
  <span style="font-size: {textSize}px">Hello</span>
</div>