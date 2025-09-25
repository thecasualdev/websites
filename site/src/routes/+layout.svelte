<script lang="ts">

	import favicon from '$lib/assets/favicon.svg';
	import './styles.css'

	let { children } = $props();

</script>

<svelte:head>

	<title>Hello, World!</title>
	<link rel="icon" href={favicon} />
	
</svelte:head>

{@render children?.()}
