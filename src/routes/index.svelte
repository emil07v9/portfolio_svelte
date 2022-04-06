<script>
	import Hero from './Hero.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<Hero />
	<section class="md:mx-20 lg:mx-40 xl:mx-60">
		<article class="flex justify-center text-center">
			<div class="borderboks px-5 py-20">
				<h3>HI!</h3>
				<h3>MY NAME IS EMILIE SCHULTZ</h3>
				<h5>
					I'M A MULTIMEDIADESIGN STUDENT WITH A BIG INTEREST IN UX & UI DESIGN... <br /> WELCOME TO MY
					PORTFOLIO!
				</h5>
			</div>
			<!-- <div class="borderboks w-80 h-96 relative mt-10">
				<div>
					<img class=" w-80 absolute left-8 top-10" src="tegning.png" alt="" />
				</div>
			</div> -->
		</article>
	</section>
	<section class="sectiontwo">
		<article class="md:px-20 lg:px-40 xl:px-60 py-10 px-1">
			<h2 class="mb-5 md:mb-10">RECAP</h2>
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
					<h4>PERSONALITY TRAITS</h4>
					<p>Energetic</p>
					<p>Positive</p>
					<p>Outgoing</p>
					<p>Caring</p>
					<p>Love a good laugh!</p>
				</div>
				<div class="pb-6">
					<h4>PROGRAMS I LIKE</h4>
					<p>Adobe XD</p>
					<p>Adobe Illustrator</p>
					<p>Figma</p>
					<p>Adobe Photoshop</p>
				</div>
				<div class="pb-6">
					<h4>OTHER PROGRAMS USED</h4>
					<p>Adobe Premiere Pro</p>
					<p>Adobe InDesign</p>
				</div>
				<div class="pb-6">
					<h4>CODING SKILLS</h4>
					<p>HTML</p>
					<p>CSS</p>
					<p>Tailwind CSS</p>
					<p>JavaScript</p>
					<p>Svelte</p>
					<p>SvelteKit</p>
				</div>
				<div class="pb-6">
					<h4>OTHER SKILLS</h4>
					<p>SEO</p>
					<p>Content creation</p>
				</div>
			</div>
		</article>
	</section>

	<Prefooter knap1="PROJECTS" knap2="ABOUT" />
	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#"><img class="puls" src="pil.svg" alt="" /></a>
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
