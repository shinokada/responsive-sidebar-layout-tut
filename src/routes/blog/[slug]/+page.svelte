<script lang="ts">
	// src/routes/blog/[slug]/+page.svelte
	import type { PageData } from './$types';
	export let data: PageData;
</script>

<svelte:component this={data.content} />
