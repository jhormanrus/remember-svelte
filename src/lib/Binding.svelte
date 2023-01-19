<script>
  let replay = false
	let volume = 1
  let lorem = 'lorem ipsum dolor isamet'
</script>

<input type="checkbox" bind:checked={replay}> replay

<input type="range" bind:value={volume}>
{typeof volume} {volume}

<br>

<textarea bind:value={lorem}></textarea>