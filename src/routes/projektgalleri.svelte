<script>
	import Cardprojectleft from './Cardprojectleft.svelte';
	import Cardprojectright from './Cardprojectright.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<section class="mt-20 md:mx-20 lg:mx-40 xl:mx-60">
		<h1 class="slide-in-top-side">PROJECTS</h1>
		<article class="slide-in-bottom-side">
			<Cardprojectleft
				src="DoLah.png"
				title="DO LAH SOAP BARS"
				text="Lorem Ipsum"
				type="2. Sem"
				link="/dolah"
			/>

			<Cardprojectright
				src="Glitch.png"
				title="TYPOGRAPHY"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/glitch"
			/>

			<Cardprojectleft
				src="SkoleMad.png"
				title="SKOLEMAD.DK"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/skolemad"
			/>

			<Cardprojectright
				src="Glitch.png"
				title="MUSIKLOFTET"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/musikloftet"
			/>

			<Cardprojectleft
				src="SkoleMad.png"
				title="UNGDOMSBYEN"
				text="Lorem Ipsum"
				type="2. Sem"
				link="/dolah"
			/>

			<Cardprojectright
				src="Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/dolah"
			/>
		</article>
	</section>
	<Prefooter knap1="CONTACT" knap2="ABOUT" />
	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#"><img class="puls" src="pil.svg" alt="" /></a>
	</div>
</main>

<style>
</style>
