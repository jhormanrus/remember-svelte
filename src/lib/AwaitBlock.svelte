<script>
  async function getVerse() {
    const res = await fetch('https://biblia.my.to/book/gen/chapter/1/verse/1')
    const text = await res.json()
    if (res.ok) {
      return text
    } else {
      throw new Error(text)
    }
  }

  let promise = getVerse()
</script>

{#await promise}
  Loading ...
{:then verse}
  {verse[0].content}
{:catch error}
  error: {JSON.strigify(error)}
{/await}
