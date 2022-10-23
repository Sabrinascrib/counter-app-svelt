<script>
	let count = 1;

		const increment = () => {
		count++;
	}
		const decrement = () => {
		count--;
	}
</script>

<main>
	<p>{count}</p>
	<button on:click={increment}>+</button>
	<button on:click={decrement}>-</button>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

</style>