<script lang="ts">
	import DefaultMetaTags from './DefaultMetaTags.svelte';
	import Footer from './Footer.svelte';
</script>

<DefaultMetaTags />

<div class="min-h-screen bg-gray-900 flex flex-col">
	<!-- <Header /> -->
	<main class="layout" py="8">
		<slot />
	</main>
	<Footer />
</div>
