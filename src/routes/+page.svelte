<script lang="ts">
	import BlogPostCard from '$lib/BlogPostCard.svelte';
	import blogIcon from '$lib/assets/testasset.jpeg';

	const posts = [
		{
			title: 'Foo bar baz',
			imgSrc: blogIcon,
			path: '/foo'
		}
	];
</script>

<svelte:head>
	<title>Skyler Arnold</title>
	<meta name="description" content="Skyler Arnold's Personal Website" />
	<meta name="keywords" content="Skyler Arnold Software Engineering Science Blog" />
</svelte:head>

<div class="gap-4 p-4 grid grid-cols-1 md:grid-cols-3">
	{#each posts as { title, imgSrc, path }}
		<BlogPostCard src={imgSrc} {title} {path} />
	{/each}
</div>
