<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	import "../lib/styles/global.scss";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>danub.dev</title>

  <link
    href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600;700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<main>
	{@render children?.()}
</main>
