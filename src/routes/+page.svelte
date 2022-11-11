<script lang="ts">
	import BlogPostCard from '$lib/BlogPostCard.svelte';

	const posts = [
		{
			title: 'Foo bar baz',
			imgSrc: 'https://source.unsplash.com/800x800/?building',
			path: '/foo'
		}
	];
</script>

<div class="gap-4 p-4 grid grid-cols-1 md:grid-cols-3">
	{#each posts as { title, imgSrc, path }}
		<BlogPostCard src={imgSrc} {title} {path} />
	{/each}
</div>
