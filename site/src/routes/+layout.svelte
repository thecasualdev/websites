<script lang="ts">

	import favicon from '$lib/assets/favicon.svg';
	import { page } from '$app/state'
	import './styles.css'

	let { children } = $props();

</script>

<svelte:head>

	<title>Hello, World!</title>
	<link rel="icon" href={favicon} />

	<meta property="og:link" content={page.url.href}>
	
</svelte:head>

{@render children?.()}
