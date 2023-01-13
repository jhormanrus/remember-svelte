<script>
  const fruits = [
    { fruit: 'apple', color: 'red' },
    { fruit: 'banana', color: 'yellow' },
    { fruit: 'lima', color: 'green' }
  ]
</script>

{#each fruits as { fruit, color }, i}
  <button>{i} - {fruit} is {color}</button>
{/each}