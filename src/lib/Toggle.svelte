<script>
	function toggleTheme() {
		const theme = document.getElementsByTagName('link')[2];

		if (theme.getAttribute('href') == 'https://cdn.jsdelivr.net/npm/water.css@2/out/dark.css') {
			theme.setAttribute('href', 'https://cdn.jsdelivr.net/npm/water.css@2/out/light.css');
		} else {
			theme.setAttribute('href', 'https://cdn.jsdelivr.net/npm/water.css@2/out/dark.css');
		}
	}
</script>

<button on:click={toggleTheme}>Switch Theme</button>

<style>
	button {
		margin: 1.5rem;
	}
</style>
