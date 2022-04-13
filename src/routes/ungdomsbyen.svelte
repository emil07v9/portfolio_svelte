<script>
	import Prefooter from './Prefooter.svelte';
</script>

<div class="ml-2 md:ml-10">
	<a sveltekit:prefetch href="/projektgalleri"
		><button class="flex justify-center"><img class="pil" src="gåfra.svg" alt="" /></button></a
	>
</div>
<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-10">
	<h1>UNGDOMS-BYEN</h1>
	<div class="md:flex space-x-2">
		<p>2. sem</p>
		<hr class="flex self-center my-1" />
		<p>INFORMATIONARCHITECTURE / CMS-SYSTEMS / UX / GRAPHIC DESIGN / SEO</p>
	</div>
	<img class="w-full h-96 mt-10 mb-20 md:mb-40" src="placeholder.png" alt="" />
	<article class="md:grid md:grid-cols-2 mb-20 md:mb-40">
		<div>
			<h2>PRJ /</h2>
			<h3>INTRODUCTION</h3>
		</div>
		<p>
			In this project we were given the task to develop a websolution that conveys
			Ungdomsbyen/"Youthtowns" many offers in an easy and clear way. We had to make suggestions to
			optimize the structure, design and SEO to ultimatly achieve a better userexperience.
		</p>
	</article>
	<article class="md:grid grid-cols-2 mb-20 md:mb-40">
		<img src="placeholder.png" alt="" />
		<div class="md:pl-4">
			<h4 class="mb-4 mt-5 md:mt-0">PRJ / INFO</h4>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Duration</p>
				<p>1 month</p>
			</div>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Type</p>
				<p>Group project</p>
			</div>
			<div class="grid grid-cols-2 mb-3">
				<p class="boxheadings">My main focus</p>
				<p>Research & analysis, informationarchitecture and SEO</p>
			</div>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Programs etc.</p>
				<p>
					Adobe Illustrator (Graphic elements), <br />
					Google Page Speed Insight (SEO),<br /> Lighthouse (SEO),
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
		<div class="md:grid grid-cols-3 mx-3 md:mx-0">
			<div class="mb-5 md:mb-0 md:mr-8">
				<h4 class="pb-1">Research & analysis</h4>
				<li class="pb-2">Analysis of the current website <br /> - moodboards, styletile</li>
				<li class="pb-2">Target group analysis <br /> - Personas & Empathy map</li>
				<li class="pb-2">Business analysis <br /> - Golden Circle & Business Model Canvas</li>
				<li class="pb-2">SWOT</li>
			</div>
			<div class="mb-5 md:mb-0 md:mr-8">
				<h4 class="pb-1">UI & UX</h4>
				<li class="pb-2">
					Interaction development <br /> - Conceptual & detailed sitemaps, cardsorting & wireframes
				</li>
				<li class="pb-2">
					Design <br /> - Moodboard, styletile, graphics & mockup
				</li>
			</div>
			<div class="mb-5 md:mb-0">
				<h4 class="pb-1">SEO</h4>
				<li class="pb-2">Technical SEO <br /> - Image compression, metadescribtions etc.</li>
				<li class="pb-2">Content SEO <br /> - Keywords & implementation</li>
				<li class="pb-2">Linkbuilding <br /> - Potential partners</li>
			</div>
		</div>
	</article>
</section>
<article class="md:grid grid-cols-4">
	<img class="hidden md:block" src="placeholder.png" alt="" />
	<img class="hidden md:block" src="placeholder.png" alt="" />
	<img src="placeholder.png" alt="" />
	<img src="placeholder.png" alt="" />
</article>
<Prefooter knap1="PROJECTS" knap2="ABOUT" />
<div class="flex justify-end mt-10">
	<a class="rotate-180 mr-5" href="#"><img class="puls" src="pil.svg" alt="" /></a>
</div>

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

	button {
		height: 60px;
		width: 60px;
	}

	button:hover {
		border: solid 1px var(--nav-color);
		background-color: white !important;
	}
</style>
