<script>
	let count = 1;

		const increment = () => {
		count++;
	}
		const decrement = () => {
		count--;
	}
</script>
<div class="wrapper-2">
<div class="wrapper"><main>
	<h1>Counter App</h1>
	<p>{count}</p>
	<button on:click={increment}>+</button>
	<button on:click={decrement}>-</button>
</main></div></div>


<style>

:root {
	font-family: Arial, Helvetica, sans-serif;
}

.wrapper-2 {
	display: flex;
	align-items: center;
	justify-content: center;
	height: 100vh;
	width: 100vw;
	background-color: #fff;
}

.wrapper {
	display: flex;
	background-color: #ff004c;
	width: 700px;
	height: 580px;
	border-radius: 5px;
	align-items: center;
	box-shadow: inset 0em 0em 20px rgba(0, 0, 0, 0.243);

}

	main {
		text-align: center;
		padding: 1em;
		width: 400px;
		height: 280px;
		margin: 0 auto;
			color: #ff004c;
			background-color: #fff;
			border-radius: 5px;
				box-shadow: 0em 0em 20px rgba(0, 0, 0, 0.243);
	}

	h1 {
		font-size: 35px;
		text-transform: uppercase;
	}

	p {
		color: #333;
		font-weight: 800;
		font-size: 35px;
	}

	button {
		color: #fff;
		background-color:#ff004c;
		border: none;
		padding: 5px 20px;
		font-size: 20px;
		font-weight: 800;
		border-radius: 5px;
		margin: 0 10px;

	}

</style>