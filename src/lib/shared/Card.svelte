<script lang="ts">
	export let content: string = `Cartea de bucate\nȚâțe afumate\nMușchiuleț de pulă\nFloci la saramură`;
	export let author: string = 'Eli';
</script>

<div class="card">
	<p>{content}</p>
	<name> - {author}</name>
</div>

<style>
	.card {
		background-color: white;
		padding: 2rem;
		border-radius: 10px;
		box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
		max-width: 55rem;
		text-align: center;
	}

	p {
		font-size: clamp(1rem, 7.5vw, 3rem);
		white-space: pre-wrap;
	}

	name {
		display: inline-block;
		width: 100%;
		font-size: clamp(1rem, 5vw, 2rem);
		margin-top: 1rem;
	}
</style>
