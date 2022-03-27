<script>
	import Hero from './Hero.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<Hero />
	<section class="md:mx-20 lg:mx-40 xl:mx-60">
		<h3 class="flex justify-center text-center">
			VELKOMMEN! <br />
			MIT NAVN ER EMILIE SCHULTZ
		</h3>
		<h4 class="flex justify-center text-center">
			JEG ER EN DIGITAL DESIGNER MED FORKÆRLIGHED FOR...
		</h4>
	</section>
	<section class="md:mx-20 lg:mx-40 xl:mx-60">
		<h2>SKILLS</h2>
		<div class="grid grid-cols-8 grid-rows-4">
			<img class="col-start-4" src="/src/img/figma.svg" alt="" />
			<img class="row-start-3" src="/src/img/adobe.svg" alt="" />
			<img class="row-start-2 col-start-6" src="/src/img/figma.svg" alt="" />
			<img class="col-start-2 row-start-2" src="/src/img/adobe.svg" alt="" />
			<img class="col-start-8 row-start-3" src="/src/img/figma.svg" alt="" />
			<img class="col-start-6 row-start-4" src="/src/img/adobe.svg" alt="" />
			<img class="col-start-2 row-start-4" src="/src/img/figma.svg" alt="" />
			<img class="col-start-7" src="/src/img/adobe.svg" alt="" />
		</div>
	</section>
	<Prefooter knap1="PROJEKTER" knap2="OM MIG" />
</main>

<style>
	section {
		margin-top: 4rem;
	}

	img {
		width: 25px;
	}
</style>
