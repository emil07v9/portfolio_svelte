<script>
	import Prefooter from './Prefooter.svelte';
	import Header from './Header.svelte';
</script>

<Header />
<main id="top">
	<div class="ml-2 md:ml-10">
		<a sveltekit:prefetch href="/projects"
			><button class="knap flex justify-center"><img class="pil" src="gåfra.svg" alt="" /></button
			></a
		>
	</div>
	<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-10">
		<h1>SKOLEMAD</h1>
		<div class="md:flex space-x-2">
			<p>3. sem</p>
			<hr class="flex self-center my-1" />
			<p>DESIGN SYSTEMS / UI & UX DESIGN / INFORMATIONARCHITECTURE / WEB DEVELOPMENT</p>
		</div>
		<img class="w-full h-96 mt-10 mb-20 md:mb-40 object-cover" src="skole1.jpg" alt="" />
		<article class="md:grid md:grid-cols-2 mb-20 md:mb-40">
			<div>
				<h2>PRJ /</h2>
				<h3>INTRODUCTION</h3>
			</div>
			<p>
				In this smaller project we were given the task to optimize and improve the UX/UI design and
				purchaseflow on Skolemad.dk. <strong>OBS!</strong> The whole site is not clickable: The task
				was only to design and develop pages relevant to the purchaseflow.
			</p>
		</article>
		<article class="md:grid grid-cols-2 mb-20 md:mb-40">
			<img src="skole2.png" alt="" />
			<div class="md:pl-4">
				<h4 class="mb-4 mt-5 md:mt-0">PRJ / INFO</h4>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Duration</p>
					<p>1 week</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Type</p>
					<p>Group project</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Programs etc.</p>
					<p>
						Figma (Prototyping etc), <br /> Adobe Illustrator (icons) <br />
					</p>
				</div>
				<div class="grid grid-cols-2 mb-3">
					<p class="boxheadings">My main focus</p>
					<p>Webdesign, <br /> Information Architecture, <br /> Design System</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Coding</p>
					<p>
						Svelte.Kit <br />
					</p>
				</div>
			</div>
		</article>
		<article class="mb-20 md:mb-40">
			<h3>PROCES OVERVIEW</h3>
			<div class="md:grid grid-cols-3 mx-3 md:mx-0">
				<div class="mb-5 md:mb-0 md:mr-8">
					<h4 class="pb-1">UX & Information Architecture</h4>
					<li class="pb-2">Conceptual Sitemap</li>
					<li class="pb-2">Detailed Sitemap</li>
					<li class="pb-2">Purchaseflow</li>
				</div>
				<div class="mb-5 md:mb-0 md:mr-8">
					<h4 class="pb-1">Design System</h4>
					<li class="pb-2">Componentbased design <br /> - SvelteKit</li>
					<li class="pb-2">Figma: Design Manual <br /> - Sizes, colors, paddings etc.</li>
				</div>
				<div class="mb-5 md:mb-0">
					<h4 class="pb-1">Website</h4>
					<li class="pb-2">Moodboard</li>
					<li class="pb-2">Styletile</li>
					<li class="pb-2">Wireframe</li>
					<li class="pb-2">Mockup</li>
				</div>
			</div>
		</article>
	</section>
	<article class="md:grid md:grid-cols-2 lg:grid-cols-4">
		<img src="skole3.png" alt="" />
		<img src="skole4.png" alt="" />
		<img src="skole5.png" alt="" />
		<img src="skole6.png" alt="" />
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
