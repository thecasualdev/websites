<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<title>websites / thecasualdev</title>
</svelte:head>

{@render children?.()}
