<script>
  let accept = 0

  let fruits = ['melon']
</script>

<label>
  <input bind:group={accept} type="radio" value={1} />
  Si
</label>

<label>
  <input bind:group={accept} type="radio" value={0} />
  No
</label>

<label>
  <input bind:group={fruits} type="checkbox" id="melon" value="melon" />
  Melon
</label>

<label>
  <input bind:group={fruits} type="checkbox" id="pinia" value="pinia" />
  Pinia
</label>