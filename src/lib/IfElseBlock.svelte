<script>
  let apple = true
  let tea = false
</script>

{#if apple && tea}
  <span>I'm a apple tea</span>
{:else if apple}
  <span>I'm a apple</span>
{:else}
  <span>no I'm not</span>
{/if}