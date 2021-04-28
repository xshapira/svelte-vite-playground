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
		<strong>normalize.css, water.css, font-awesome 5, stylelint & eslint</strong> pre configured.
		<br /><br />

		<strong>
			<span><i class="fas fa-info-circle" /></span>&nbsp; Assumes Prettier is already configured.</strong>
	</p>
</main>

<style>
	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height: 100vh;
		text-align: center;
	}

	img {
		width: 5rem;
		height: 5rem;
	}
</style>
