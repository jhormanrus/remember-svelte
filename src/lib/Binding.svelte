<script>
	let volume = 1
  let replay = false
</script>

<input type="checkbox" bind:checked={replay}> replay

<input type="range" bind:value={volume}>
{typeof volume} {volume}