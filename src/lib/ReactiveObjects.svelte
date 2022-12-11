<script>
  let arr = [1, 2, 3]

  $: sum = () => {
    return arr.reduce((t, n) => t + n, 0)
  }

  function addNumber() {
    // arr.push(arr.length + 1)
    // arr = arr

    // arr = [...arr, arr.length + 1]

    arr[arr.length] = arr.length + 1
  }
</script>

<span>{arr.join(', ')}</span> = {sum()}
<button on:click={addNumber}>+1</button>