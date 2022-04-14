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
		<h1>ANIMATION GAME</h1>
		<div class="md:flex space-x-2">
			<p>1. sem</p>
			<hr class="flex self-center my-1" />
			<p>ILLUSTRATING / ANIMATION DESIGN / JAVASCRIPT / HTML & CSS</p>
		</div>
		<img class="w-full mt-10 mb-20 md:mb-40 object-cover" src="anim1.png" alt="" />
		<article class="md:grid md:grid-cols-2 mb-20 md:mb-40">
			<div>
				<h2>PRJ /</h2>
				<h3>INTRODUCTION</h3>
			</div>
			<p>
				In this project we were introduced to Javascript for the first time. Each we had to devise,
				design, draw and finally code our own simpel "click"-game. Furthermore vi had to record our
				own soundeffects, find fitting background music and implement these in the game.
			</p>
			<a
				target="_blank"
				class="flex justify-center col-span-2 pt-5"
				href="https://emilieschultz.dk/kea/04_animation/spil_battle_z/"><button>GAME</button></a
			>
		</article>
		<article class="md:grid grid-cols-2 mb-20 md:mb-40">
			<img class="h-80 object-cover" src="anim2.png" alt="" />
			<div class="md:pl-4">
				<h4 class="mb-4 mt-5 md:mt-0">PRJ / INFO</h4>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Duration</p>
					<p>1 month</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Type</p>
					<p>Individual project</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Programs etc.</p>
					<p>
						Adobe Illustrator (spilfigurer, baggrunde etc.) <br /> Adobe Audition (lydeffekter)
					</p>
				</div>
				<div class="grid grid-cols-2 mb-2">
					<p class="boxheadings">Coding</p>
					<p>
						JavaScript <br />
						HTML <br />
						CSS <br />
					</p>
				</div>
			</div>
		</article>
		<article class="mb-20 md:mb-40">
			<h3>PROCES OVERVIEW</h3>
			<div class="md:grid grid-cols-3 mx-3 md:mx-0">
				<div class="mb-5 md:mb-0 md:mr-8">
					<h4 class="pb-1">Idea & koncept</h4>
					<li class="pb-2">Concept development</li>
					<li class="pb-2">Paperprototyping</li>
					<li class="pb-2">Activitydiagram</li>
					<li class="pb-2">State Machine Diagram</li>
				</div>
				<div class="mb-5 md:mb-0 md:mr-8">
					<h4 class="pb-1">Design & implementation</h4>
					<li class="pb-2">Moodboard</li>
					<li class="pb-2">Sketching <br /> - Gamepages, backgrounds, characters</li>
					<li class="pb-2">Finished drawings of sketches<br /> - Adobe Illustrator</li>
				</div>
				<div class="mb-5 md:mb-0 md:mr-8">
					<h4 class="pb-1">Soundeffects</h4>
					<li class="pb-2">Recording</li>
					<li class="pb-2">Editing in Audition</li>
				</div>
			</div>
		</article>
	</section>
	<article class="md:grid grid-cols-4">
		<img src="anim3.png" alt="" />
		<img src="anim4.png" alt="" />
		<img src="anim5.png" alt="" />
		<img src="anim6.png" alt="" />
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
