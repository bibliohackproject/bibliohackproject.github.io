<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<header class="bg-slate-800 text-white p-4">
	<div class="max-w-6xl mx-auto">
		<h1>bibliohack project</h1>
	</div>
</header>

<main class="bg-slate-100 max-w-6xl mx-auto">
	{@render children()}
</main>

<footer class="bg-slate-800 text-white p-4">
	<div class="max-w-6xl mx-auto">
		<p class="text-sm font-zalando-sans-expanded">bibliohack project</p>
	</div>
</footer>