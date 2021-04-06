<script lang="ts">
	import { onMount } from 'svelte';

	let ably = null
	// just so i don't have unused import warnings
	onMount(async () => {
    const module = await import('ably')
		ably = module.default
	})

	// or
</script>

<main>
	<h1>hello world</h1>
</main>