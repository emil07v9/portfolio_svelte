<script>
	import Hero from './Hero.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<Hero />
	<section class="md:mx-20 lg:mx-40 xl:mx-60">
		<article class="md:grid grid-cols-2 gap-8">
			<div>
				<h2>HI!</h2>
				<h3>MY NAME IS EMILIE SCHULTZ</h3>
				<h5>
					I'M A MULTIMEDIADESIGN STUDENT WITH BIG INTEREST IN UX & UI DESIGN... WELCOM TO MY
					PORTFOLIO!
				</h5>
			</div>
			<div class="borderboks w-80 h-96 relative mt-10">
				<div>
					<img class=" w-80 absolute left-8 top-10" src="src/img/tegning.png" alt="" />
				</div>
			</div>
		</article>
	</section>
	<section class="sectiontwo">
		<article class="md:px-20 lg:px-40 xl:px-60 py-10 px-1">
			<h2 class="mb-5 md:mb-10">WALL OF SKILLS</h2>
			<div class="md:grid grid-cols-3 gap-10">
				<div class="pb-6">
					<h4>PROFESSIONAL TRAITS</h4>
					<p>Structured</p>
					<p>Flexible approach to new tasks</p>
					<p>Serviceminded</p>
					<p>Thrives in teamwork</p>
					<p>Quality oriented</p>
					<p>Independent</p>
				</div>
				<div class="pb-6">
					<h4>HEJ</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, nam.</p>
				</div>
				<div class="pb-6">
					<h4>HEJ</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, nam.</p>
				</div>
				<div class="pb-6">
					<h4>PERSONALITY TRAITS</h4>
					<p>Energetic</p>
					<p>Positive</p>
					<p>Outgoing</p>
					<p>Caring</p>
					<p>Love a good laugh!</p>
				</div>
				<div class="pb-6">
					<h4>HEJ</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, nam.</p>
				</div>
				<div class="pb-6">
					<h4>HEJ</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, nam.</p>
				</div>
			</div>
		</article>
	</section>

	<Prefooter knap1="PROJECTS" knap2="ABOUT" />
	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#"><img class="puls" src="src/img/pil.svg" alt="" /></a>
	</div>
</main>

<style>
	.borderboks {
		border: 2px solid var(--nav-color);
	}
	.sectiontwo {
		background-color: var(--grey-color);
	}

	p {
		max-width: 60ch;
	}
</style>
