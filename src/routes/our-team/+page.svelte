<script>
	import Origin from "../../lib/Our Team/Team/Team.svelte";
	import Animate from "../../lib/Animate.svelte";
	import Hero from "../../lib/Components/Hero/Hero.svelte";
</script>

<svelte:head>
	<title>The team | Plantesk</title>
	<meta name="description" content="The team at Plantesk" />
	<link rel="canonical" href="https://plantesk.netlify.app/our-team/" />
</svelte:head>

<Animate>
	<section>
		<Hero title="Our Team" image="5" desc="Meet our team who make this site possible" />
		<Origin />
	</section>
	
</Animate>