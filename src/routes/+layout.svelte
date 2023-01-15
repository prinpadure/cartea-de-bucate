<script>
	import './styles.css';
</script>

<div class="app">
	<header />
	<main>
		<slot />
	</main>
	<footer />
</div>

<style>
	main {
		/* margin-top: 2rem; */
		width: min(90%, 900px);
		margin: 0 auto;
		padding: 2rem 0.75rem;
	}
	.app {
		min-height: 100vh;
	}
</style>
