<script>
  let count = 5
  let tripled = 0
  $: doubled = count * 2
  $: {
    console.log(count)
    tripled = count * 3
  }
  $: if (count > 10) {
    count = 0
  }

  function handleClick () {
    count += 1
  }
</script>

<span>{count} doubled is {doubled} and tripled is {tripled}</span>
<button on:click={handleClick}>+1</button>
