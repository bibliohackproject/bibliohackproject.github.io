<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>bibliohack project</title>
	<meta
		name="description"
		content="テクノロジーを活用し、本の情報を共有し、発見するさまざまなサービスを開発・提供することを目指すプロジェクトです。"
	/>
	<meta property="og:type" content="website" />
	<meta property="og:site_name" content="bibliohack project" />
	<meta property="og:title" content="bibliohack project" />
	<meta
		property="og:description"
		content="テクノロジーを活用し、本の情報を共有し、発見するさまざまなサービスを開発・提供することを目指すプロジェクトです。"
	/>
	<meta property="og:url" content="https://bibliohackproject.github.io/" />
	<meta property="og:image" content="https://bibliohackproject.github.io/ogp.png" />
	<meta property="og:image:width" content="1200" />
	<meta property="og:image:height" content="630" />
	<meta name="twitter:card" content="summary_large_image" />
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