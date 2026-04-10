<script>
	import { formatDate } from "$lib/utils.js";
	import PageTitle from '$lib/components/PageTitle.svelte'
	import Section from '$lib/components/Section.svelte'
	import Card from '$lib/components/Card.svelte'

	const { data } = $props()
</script>

<PageTitle title="Portfolio" />

<Section headingText="My Projects" layout="auto-fill padding-bottom-3">
	{#each data.posts as post}
		<Card
			image={post.meta.image}
			eyebrow={formatDate(post.meta.date)}
			title={post.meta.title}
			excerpt={post.meta.excerpt}
			href={'/portfolio/' + post.slug}
		/>
	{/each}
</Section>
