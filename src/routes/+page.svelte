<script lang="ts">
	import LandingText from '$lib/components/Home/LandingText.svelte';
	import PortfolioImage from '$lib/components/Home/PortfolioImage.svelte';
</script>

<main class="items-center inline-block p-3 pt-0 mx-auto max-w-8xl lg:flex lg:flex-wrap lg:pt-4">
	<LandingText />
	<PortfolioImage />
</main>

<style>
	main {
		display: grid;
		grid-template-columns: repeat(2, 1fr);
		height: 80vh;
		width: 100%;
		background-color: rgb(255, 255, 255);
        padding: 8rem;
	}
</style>
