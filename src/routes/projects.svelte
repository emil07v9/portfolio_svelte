<script>
	import Cardprojectleft from './Cardprojectleft.svelte';
	import Cardprojectright from './Cardprojectright.svelte';
	import Prefooter from './Prefooter.svelte';
	import Header from './Header.svelte';
</script>

<Header />
<main id="top">
	<section class="mt-20 md:mx-20 lg:mx-40 xl:mx-60">
		<h1 class="slide-in-top-side">PROJECTS</h1>
		<article class="slide-in-bottom-side">
			<Cardprojectleft src="DoLah.png" title="DO LAH SOAP BARS" type="2. Sem" link="/dolah" />

			<Cardprojectright src="Glitch.png" title="TYPOGRAPHY" type="3. Sem" link="/glitch" />

			<Cardprojectleft src="SkoleMad.png" title="SKOLEMAD.DK" type="3. Sem" link="/skolemad" />

			<Cardprojectright
				src="musikloftet.png"
				title="MUSIKLOFTET"
				type="3. Sem"
				link="/musikloftet"
			/>

			<Cardprojectleft
				src="ungdomsbyen.png"
				title="UNGDOMSBYEN"
				type="2. Sem"
				link="/ungdomsbyen"
			/>

			<Cardprojectright
				src="spil.png"
				title="ANIMATION GAME"
				type="1. Sem"
				link="/animationsspil"
			/>
		</article>
	</section>
	<Prefooter knap1="CONTACT" link1="/contact" knap2="ABOUT" link2="/about" />
	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#top"><img class="puls" src="pil.svg" alt="" /></a>
	</div>
</main>

<style>
</style>
