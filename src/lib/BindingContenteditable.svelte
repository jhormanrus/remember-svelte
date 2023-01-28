<script>
  let html = '<span>Content editable</span>'
</script>

<div contenteditable="true" bind:innerHTML={html}></div>

<style>
  [contenteditable] {
    border: 1px solid black;
  }
</style>