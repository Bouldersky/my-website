<script lang="ts">
	export let src: string;
	export let title: string;
	export let path: string;
</script>

<a href={path}>
	<div
		class="bg-gray-50 h-56 rounded-lg overflow-hidden shadow-md hover:shadow-lg transition ease-in-out duration-250"
	>
		<img class="w-full h-3/4 object-cover" {src} alt={title} />
		<div class="p-2 text-gray-800">
			{title}
		</div>
	</div>
</a>
