<script>
	import Prefooter from './Prefooter.svelte';
</script>

<div class="ml-2 md:ml-10">
	<a sveltekit:prefetch href="/projektgalleri"
		><button class="flex justify-center"><img class="pil" src="gåfra.svg" alt="" /></button></a
	>
</div>
<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-10">
	<h1>MUSIKLOFTET</h1>
	<div class="md:flex space-x-2">
		<p>3. sem</p>
		<hr class="flex self-center my-1" />
		<p>DESIGN SYSTEMS / UI & UX DESIGN / INFORMATIONARCHITECTURE / WEB DEVELOPMENT</p>
	</div>
	<img class="w-full h-96 mt-10 mb-20 md:mb-40" src="placeholder.png" alt="" />
	<article class="md:grid md:grid-cols-2 mb-20 md:mb-40">
		<div>
			<h2>PRJ /</h2>
			<h3>INTRODUCTION</h3>
		</div>
		<p>
			In this smaller project we were given the task to create a website for the fictional music
			rehearsal room landlord, 'Musikloftet'. The website had to give a good overview of the
			different services, Musikloftet had to offer, as well as visually reflect what type of place,
			you could expect to meet. Furthermore the design had to be shaped around a list of values...
			<br /> My group chose these three words: <br />
			Immersion, flexibility and focus.
		</p>
	</article>
	<article class="md:grid grid-cols-2 mb-20 md:mb-40">
		<img src="placeholder.png" alt="" />
		<div class="md:pl-4">
			<h4 class="mb-4 mt-5 md:mt-0">PRJ / INFO</h4>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Duration</p>
				<p>2 week</p>
			</div>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Type</p>
				<p>Group project</p>
			</div>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Programs etc.</p>
				<p>
					Figma (Prototyping etc), <br /> Adobe Illustrator (content)
				</p>
			</div>
			<div class="grid grid-cols-2 mb-3">
				<p class="boxheadings">My main focus</p>
				<p>Idea development, <br /> Webdesign, <br /> Frontend Development</p>
			</div>
			<div class="grid grid-cols-2 mb-2">
				<p class="boxheadings">Coding</p>
				<p>
					HTML <br />
					Tailwind CSS
				</p>
			</div>
		</div>
	</article>
	<article class="mb-20 md:mb-40">
		<h3>PROCES OVERVIEW</h3>
		<div class="md:grid grid-cols-3 gap-7 mx-3 md:mx-0">
			<div class="mb-5 md:mb-0">
				<h4 class="pb-1">Design</h4>
				<li class="pb-2">Moodboard</li>
				<li class="pb-2">Styletile</li>
				<li class="pb-2">Graphic Elements</li>
			</div>
			<div class="mb-5 md:mb-0">
				<h4 class="pb-1">Website</h4>
				<li class="pb-2">Sitemap (IA)</li>
				<li class="pb-2">Wireframing</li>
				<li class="pb-2">Prototyping</li>
			</div>
			<div class="mb-5 md:mb-0">
				<h4 class="pb-1">Test</h4>
				<li class="pb-2">Usability test <br /> - Test of prototype</li>
				<li class="pb-2">Usability test <br /> - Test of website</li>
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
