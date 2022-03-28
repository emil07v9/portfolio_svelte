<script>
	import Cardprojectleft from './Cardprojectleft.svelte';
	import Cardprojectright from './Cardprojectright.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<section class="mt-20 md:mx-20 lg:mx-40 xl:mx-60">
		<h1>PROJECTS</h1>
		<article>
			<Cardprojectleft
				src="src/img/DoLah.png"
				title="DO LAH SOAP BARS"
				text="Lorem Ipsum"
				type="2. Sem"
			/>

			<Cardprojectright
				src="src/img/Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
			/>

			<Cardprojectleft
				src="src/img/SkoleMad.png"
				title="SKOLEMAD.DK"
				text="Lorem Ipsum"
				type="3. Sem"
			/>

			<Cardprojectright
				src="src/img/Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
			/>

			<Cardprojectleft
				src="src/img/SkoleMad.png"
				title="UNGDOMSBYEN"
				text="Lorem Ipsum"
				type="2. Sem"
			/>

			<Cardprojectright
				src="src/img/Glitch.png"
				title="TYPOGRAFI"
				text="Lorem Ipsum"
				type="3. Sem"
			/>
		</article>
	</section>
	<Prefooter knap1="CONTACT" knap2="ABOUT" />
</main>

<style>
</style>
