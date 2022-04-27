<script>
	import Hero from './Hero.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main id="#top">
	<Hero anchor="#one" />
	<section id="one" class="md:mx-20 lg:mx-40 xl:mx-60">
		<article class="flex justify-center py-20">
			<div class="md:grid grid-cols-5">
				<div class="text-right col-span-2">
					<h3>HI & WELCOME</h3>
					<h4>TO MY PORTFOLIO</h4>
				</div>
				<hr class="rotate-90 self-center col-span-1" />
				<div class="col-span-2">
					<h5>
						MY NAME IS EMILIE SCHULTZ & I'M A MULTIMEDIADESIGN STUDENT WITH A GREAT INTEREST IN UX &
						UI DESIGN... <br />
						TAKE A LOOK AROUND !
					</h5>
				</div>
			</div>
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
					<p>Adobe Audition</p>
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

	<Prefooter knap1="PROJECTS" link1="/projects" knap2="ABOUT" link2="/about" />

	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#top"><img class="puls" src="pil.svg" alt="" /></a>
	</div>
</main>

<style>
	hr {
		background-color: var(--nav-color);
		height: 2px;
	}
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
