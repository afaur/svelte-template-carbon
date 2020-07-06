<script>
	import { Button } from "carbon-components-svelte"
	export let name;
</script>

<svelte:head>
  <link
    rel="stylesheet"
    href="https://unpkg.com/carbon-components@10.9.0/css/carbon-components.min.css"
  />
</svelte:head>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <Button href="https://svelte.dev/tutorial">Svelte
    tutorial</Button> to learn how to build Svelte apps.</p>
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
