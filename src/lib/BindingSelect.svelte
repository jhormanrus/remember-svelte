<script>
  let value
  let valueMulti = ['Option C']
  let options = [
    'Option A',
    'Option B',
    'Option C'
  ]
</script>

<!-- by default first option is selected -->
<select bind:value>
  {#each options as option}
    <option value={option}>{option}</option>
  {/each}
</select>

<select multiple bind:value={valueMulti}>
  {#each options as option}
    <option value={option}>{option}</option>
  {/each}
</select>