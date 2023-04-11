<script>
  import {Button} from 'carbon-components-svelte'
  import {Add} from 'carbon-icons-svelte'
  let count = 0
  const increment = () => {
    count += 1
  }

</script>

<Button icon={Add} on:click={increment}>
  count is {count}
</Button>
