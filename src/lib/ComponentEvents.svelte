<script>
  import { createEventDispatcher } from 'svelte'

  const dispatch = createEventDispatcher()

  function sayHello() {
    dispatch('message', {
      text: 'hello'
    })
  }
</script>

<button on:click={sayHello}>Say hello</button>