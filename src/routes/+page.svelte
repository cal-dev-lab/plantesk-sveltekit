<script>
	import Animate from "../lib/Animate.svelte";
	import Hero from "../lib/Components/Hero/Hero.svelte";
	import Growing from "../lib/Home/Growing/Growing.svelte";
	import Plants from "../lib/Home/Plants/Plants.svelte";
	import Watering from "../lib/Home/Watering/Watering.svelte";
</script>

<svelte:head>
	<title>Home | Plantesk</title>
	<meta name="description" content="Plantesk - The home of gardening." />
	<link rel="canonical" href="https://plantesk.netlify.app/" />
</svelte:head>

<Animate>
	<section>
		<!-- START: Hero -->
		<Hero title="Plantesk" image="3" desc="The home of plants" />
		<!-- END: Hero -->

		<!-- START: Plants -->
		<Plants />
		<!-- END: Plants -->

		<!-- START: Watering -->
		<Watering />
		<!-- END: Watering -->

		<!-- START: Growing -->
		<Growing />
		<!-- END: Growing -->
	</section>
</Animate>