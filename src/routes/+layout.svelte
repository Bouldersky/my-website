<script lang="ts">
	import '../app.css';
	import Logo from '$lib/Logo.svelte';
</script>

<nav class="bg-gray-400 p-3 flex justify-center items-center gap-4">
	<Logo class="h-12" />
</nav>

<slot />
