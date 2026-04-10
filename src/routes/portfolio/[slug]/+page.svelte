<script>
	import { formatDate } from '$lib/utils.js'
	import Article from '$lib/components/Article.svelte'
	import Section from '$lib/components/Section.svelte'

	const { data } = $props()

	const Post = $derived(data.post.component)

	$inspect(data)
</script>

<Article title={data.post.meta.title}>
	<div class="grid gap-1">
		<time>{formatDate(data.post.meta.date)}</time>
		<img src={'/' + data.post.meta.image} alt="" />
	</div>
	<Post />
</Article>

<style>
	time {
		padding-top: 1rem;
	}
</style>
