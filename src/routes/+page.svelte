<script>
	import AnimationIcon from '$lib/assets/icons/icon-animation.svg'
	import BusinessIcon from '$lib/assets/icons/icon-business.svg'
	import DesignIcon from '$lib/assets/icons/icon-design.svg'
	import PhotographyIcon from '$lib/assets/icons/icon-photography.svg'
	import ProgrammingIcon from '$lib/assets/icons/icon-programming.svg'
	import Box from '$lib/components/Box.svelte'
	import HeadingBox from '$lib/components/HeadingBox.svelte'
	import Hero from '$lib/components/Hero.svelte'
	import Section from '$lib/components/Section.svelte'
</script>

<Hero />

<section class="boxes">
	<div class="skins bg-gradient-gray">
		<div class="container">
			<div class="layout auto-fill">
				<HeadingBox />
				<Box icon={AnimationIcon} />
				<Box icon={BusinessIcon} />
				<Box icon={DesignIcon} />
				<Box icon={PhotographyIcon} />
				<Box icon={ProgrammingIcon} />
			</div>
		</div>
	</div>
</section>

<style>
	.boxes {
		padding-block: 0rem;
	}
	
	.container {
		padding-block: 6rem;
	}

	.bg-gradient-gray {
		background-size: cover;
	}
</style>