<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<title>Adam Ducken - Full-Stack Web3 Developer</title>
	<meta
		name="description"
		content="Full-stack Web3 developer with 3+ years of experience using Rust and TypeScript. Experienced with Anchor, Axum, and SvelteKit."
	/>

	<!-- Open Graph / Social Media -->
	<meta property="og:type" content="website" />
	<meta property="og:title" content="Adam Ducken - Full-Stack Web3 Developer" />
	<meta
		property="og:description"
		content="Full-stack Web3 developer with 3+ years of experience using Rust and TypeScript."
	/>
	<meta property="og:url" content="https://adamducken.github.io/" />

	<link rel="icon" href={favicon} />

	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

{@render children()}
