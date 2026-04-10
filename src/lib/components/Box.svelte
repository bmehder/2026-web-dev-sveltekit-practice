<script>
	let { icon } = $props()
</script>

<div class="bg-white">
	<img src={icon} alt="" />
	<h3>Animation</h3>
	<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, dolor.</p>
	<a class="bold" href="/portfolio">Read More »</a>
</div>

<style>
	div {
		position: relative;
		padding: 2rem;
		border-radius: 1rem;
		font-size: 1.125rem;
	}

  img {
    position: absolute;
    width: 3.5rem;
    margin-top: -3.5rem;
  }
</style>
