<script>
	import { Button, Header } from "svantic";
	let count = 0;
</script>

<main>
	<Header>
		Svantic Template
		<Header.sub>You clickded {count} times</Header.sub>
	</Header>

	<Button icon="hand peace" on:click={() => count++}>Hello world</Button>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
</style>
