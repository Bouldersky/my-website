<script lang="ts">
	import '../app.css';
	import Logo from '$lib/Logo.svelte';
</script>

<nav class="bg-gray-400 p-3 flex justify-between items-center">
	<Logo class="h-12" />
</nav>

<slot />
