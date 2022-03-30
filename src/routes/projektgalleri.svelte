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
				src="/img/DoLah.png"
				title="DO LAH"
				text="Lorem Ipsum"
				type="2. Sem"
				link="/dolah"
			/>

			<Cardprojectright
				src="/img/Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/dolah"
			/>

			<Cardprojectleft
				src="/img/SkoleMad.png"
				title="SKOLEMAD.DK"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/dolah"
			/>

			<Cardprojectright
				src="/img/Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/dolah"
			/>

			<Cardprojectleft
				src="/img/SkoleMad.png"
				title="UNGDOMSBYEN"
				text="Lorem Ipsum"
				type="2. Sem"
				link="/dolah"
			/>

			<Cardprojectright
				src="/img/Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
				link="/dolah"
			/>
		</article>
	</section>
	<Prefooter knap1="CONTACT" knap2="ABOUT" />
	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#"><img class="puls" src="/img/pil.svg" alt="" /></a>
	</div>
</main>

<style>
</style>
