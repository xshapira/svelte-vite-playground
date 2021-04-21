<script>
	import logo from './assets/svelte.png';
	import Toggle from './lib/Toggle.svelte';
</script>

<main class="container">
	<Toggle />

	<img src={logo} alt="Svelte Logo" />
	<h1>Svelte Playground</h1>
	<p>
		This is a svelte template scaffolded with <strong>vitejs</strong> & comes with
		<strong>normalize.css, water.css, font-awesome 5 & stylelint</strong> pre configured.
		<br /><br />

		<strong>
			<span><i class="fas fa-info-circle" /></span>&nbsp; Assumes Prettier is already configured.</strong>
	</p>
</main>

<style>
	.container {
		text-align: center;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height: 100vh;
	}

	img {
		height: 5rem;
		width: 5rem;
	}
</style>
