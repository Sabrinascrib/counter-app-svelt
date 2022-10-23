<script>
	let count = 1;
</script>

<main>
	<p>{count}</p>
	<button on:click={() => count++}>+</button>
	<button on:click={() => count--}>-</button>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

</style>