<script>
  let value
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