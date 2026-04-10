<script>
	let {
		title = 'ADD A HEADING FOR A11Y!',
		article = '',
		skins = '',
		container = '',
		heading = '',
		layout = '',
		children,
	} = $props()
</script>

<article class={'article ' + article}>
	<div class={'skins ' + skins}>
		<div class={'container ' + container}>
			<div>
				<h1 class={'article_title ' + heading}>{title}</h1>
			</div>
			<div class={'layout ' + layout}>
				{@render children?.()}
			</div>
		</div>
	</div>
</article>

<style>
	h1 {
		margin: 0;
	}
</style>
