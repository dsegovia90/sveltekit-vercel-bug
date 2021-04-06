<script lang="ts">
import { browser } from '$app/env';

	import { onMount } from 'svelte';

	let ably = null
	// just so i don't have unused import warnings
	onMount(async () => {
		if (browser) {
			const module = await import('ably')
			ably = module.default
		}
	})
</script>

<main>
	<h1>hello world</h1>
</main>