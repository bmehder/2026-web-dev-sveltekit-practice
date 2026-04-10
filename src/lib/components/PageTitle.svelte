<script>
	import { formatDate } from '$lib/utils.js'

	let { title, date } = $props()
</script>

<div class="page-title">
	<div class="skins">
		<div class="container">
      <h1>{title}</h1>
      <div class="opacity-5">
        {formatDate(date)}
      </div>
		</div>
	</div>
</div>

<style>
  .container {
    margin-bottom: 1.5rem;
    border-bottom: 1px solid;
  }
</style>