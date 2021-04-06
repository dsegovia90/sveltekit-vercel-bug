<script lang="ts">
	import { browser } from '$app/env'
	import ably from "ably"
	// just so i don't have unused import warnings
	if (browser) {
		ably
	}
</script>

<main>
	<h1>hello world</h1>
</main>