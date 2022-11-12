<script lang="ts">
	import '../app.css';
	import Logo from '$lib/Logo.svelte';
</script>

<nav class="bg-gray-400 p-3 flex justify-center items-center gap-4">
	<a href="/">
		<Logo class="h-12" />
	</a>
</nav>

<slot />
