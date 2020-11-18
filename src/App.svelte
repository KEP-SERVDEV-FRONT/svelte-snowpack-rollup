<script lang="ts">
export let name: string;
let count = 0
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
  <br/>
  <button on:click={() => count++}>{count} is HMR2222</button>
</main>

<style>
main {
  text-align: center;
  padding: 1em;
  max-width: 240px;
  margin: 0 auto;
}

h1 {
  color: #ff3e00;
  text-transform: uppercase;
  font-size: 4em;
  font-weight: 100;
}


@media (min-width: 640px) {
  main {
    max-width: none;
  }
}
</style>