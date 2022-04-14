<script>
	import Prefooter from './Prefooter.svelte';
</script>

<main id="top">
	<div class="ml-2 md:ml-10">
		<a sveltekit:prefetch href="/projects"
			><button class="knap flex justify-center"><img class="pil" src="gåfra.svg" alt="" /></button
			></a
		>
	</div>
	<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-10">
		<h1>DO LAH</h1>
		<div class="md:flex space-x-2">
			<p>2. sem</p>
			<hr class="flex self-center my-1" />
			<p>DIGITAL DESIGN / CMS SYSTEMS / CONTENT CREATION / SO-ME / SEO</p>
		</div>
		<img class="w-full h-96 mt-10 mb-20 md:mb-40 object-cover" src="dolah1.png" alt="" />
		<article class="md:grid md:grid-cols-2 mb-20 md:mb-40">
			<div>
				<h2>PRJ /</h2>
				<h3>INTRODUCTION</h3>
			</div>
			<p>
				In this project we were given the task to optimize the clients online profiling through
				multimedia solutions. As a part of our solution, we created a new and improved website,
				visual ID, content, communication strategy and SEO strategy for the company.
			</p>
			<a
				target="_blank"
				class="flex justify-center col-span-2 pt-5"
				href="https://lineberner.com/kea/2_semester/dolah/"><button>WEBSITE</button></a
			>
		</article>
		<article class="md:grid grid-cols-2 mb-20 md:mb-40">
			<img src="dolah2.png" alt="" />
			<div class="md:pl-4">
				<h4 class="mb-4 mt-5 md:mt-0">PRJ / INFO</h4>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Duration</p>
					<p>1 month</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Type</p>
					<p>Exam group project</p>
				</div>
				<div class="grid grid-cols-2 mb-3">
					<p class="boxheadings">My main focus</p>
					<p>Idea development & webdesign, research & analysis, SEO and usability & user testing</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Programs etc.</p>
					<p>
						Adobe Photoshop, <br /> Adobe XD (Prototyping etc), <br />Screaming Frog (SEO),<br />
						Google Ads (SEO),<br /> Lighthouse (SEO),
						<br /> Smush & Yoast (WP SEO)
					</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Coding</p>
					<p>CMS-system, <br /> PHP</p>
				</div>
			</div>
		</article>
		<article class="mb-20 md:mb-40">
			<h3>PROCES OVERVIEW</h3>
			<div class="md:grid grid-cols-2 mx-3 md:mx-0">
				<div class="mb-5 md:mb-0 md:mr-8">
					<h4 class="pb-1">Research & analysis</h4>
					<li class="pb-2">Interview with client</li>
					<li class="pb-2">Target group analysis <br /> - Personas & Empathy map</li>
					<li class="pb-2">Testing (current website) <br /> - Heuristic test & BERT</li>
					<li class="pb-2">Business analysis <br /> - Golden Circle & Business Model Canvas</li>
					<li class="pb-2">
						Competitor analysis <br /> - Positioning model & Target model
					</li>
					<li class="pb-2">SWOT & TOWS</li>
				</div>
				<div class="mb-5 md:mb-0">
					<h4 class="pb-1">Website & testing</h4>
					<li class="pb-2">
						Interaction development <br /> - Sitemaps, content outlines & wireframes
					</li>
					<li class="pb-2">
						Design <br /> - Moodboard, styletile, graphics & mockup
					</li>
					<li class="pb-2">Split test</li>
					<li class="pb-2">Usability test</li>
					<li class="pb-2">BERT (new site)</li>
					<li class="pb-2">Heuristic inspection</li>
				</div>
				<div class="mb-5 md:mb-0 md:mr-8 md:mt-5">
					<h4 class="pb-1">Communication & content</h4>
					<li class="pb-2">Content Strategy <br /> - SMART model & KPI's</li>
					<li class="pb-2">Costumer Journeys</li>
					<li class="pb-2">Video & images<br /> - Storyboard, shooting and editing</li>
				</div>
				<div class="mb-5 md:mb-0 md:mt-5">
					<h4 class="pb-1">SEO</h4>
					<li class="pb-2">Technical SEO <br /> - Image compression, metadescribtions etc.</li>
					<li class="pb-2">Content SEO <br /> - Keywords & implementation</li>
					<li class="pb-2">Linkbuilding</li>
				</div>
			</div>
		</article>
	</section>
	<article class="md:grid md:grid-cols-2 lg:grid-cols-4">
		<img src="dolah3.png" alt="" />
		<img src="dolah4.png" alt="" />
		<img src="dolah5.png" alt="" />
		<img src="dolah6.png" alt="" />
	</article>

	<div class="flex justify-end mt-10">
		<a class="rotate-180 mr-5" href="#top"><img class="puls" src="pil.svg" alt="" /></a>
	</div>
</main>

<style>
	hr {
		width: 30px;
		background-color: var(--nav-color);
		height: 2px;
		margin-block: 10px;
	}

	.boxheadings {
		font-weight: 400;
	}

	.knap {
		height: 60px;
		width: 60px;
	}

	.knap:hover {
		border: solid 1px var(--nav-color);
		background-color: white !important;
	}
</style>
