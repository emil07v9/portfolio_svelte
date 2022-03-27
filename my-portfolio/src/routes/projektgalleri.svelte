<script>
	import Cardproject from './Cardproject.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<section class="mt-20 md:mx-20 lg:mx-40 xl:mx-60">
		<h1>PROJEKTER</h1>
		<Cardproject
			src="src/img/DoLah.png"
			title="DO LAH SOAP BARS"
			text="Lorem Ipsum"
			type="2. Sem"
		/>
		<Cardproject src="src/img/Glitch.png" title="GLITCH FONT" text="Lorem Ipsum" type="3. Sem" />
		<Cardproject src="src/img/SkoleMad.png" title="SKOLEMAD.DK" text="Lorem Ipsum" type="3. Sem" />
		<Cardproject src="src/img/SkoleMad.png" title="MUSIKLOFTET" text="Lorem Ipsum" type="3. Sem" />
		<Cardproject src="src/img/SkoleMad.png" title="UNGDOMSBYEN" text="Lorem Ipsum" type="2. Sem" />
		<Cardproject
			src="src/img/SkoleMad.png"
			title="ANIMATIONSSPIL"
			text="Lorem Ipsum"
			type="1. Sem"
		/>
	</section>
	<Prefooter knap1="KONTAKT" knap2="OM MIG" />
</main>

<style>
</style>
