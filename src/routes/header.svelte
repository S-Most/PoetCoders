<script lang="ts">
	import Toggle from './toggle.svelte'
	import * as config from '$lib/config'
</script>

<nav>
	<a href="/" class="title">
		<b>{config.title}</b>
	</a>

	<Toggle />
</nav>

<style>
	nav {
		display: flex;
		justify-content: space-between;
		padding-block: var(--size-7);
	}
</style>
