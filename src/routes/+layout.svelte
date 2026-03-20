<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
{@render children()}

<style>
	:global(body) {
		background-color: seashell;
		background-image: url("/dry-grass-ground-128x128.png");
		background-size: 512px;
		image-rendering: pixelated;
		background-repeat: repeat;

		color: rgb(255, 255, 255);
		margin: 0%;
		display: flex;
		justify-content: center;
	}

	/* a:link {
		color: red;
	}
	a:visited {
		color: red;
	} */
	
</style>