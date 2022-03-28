<script>
	import Hero from './Hero.svelte';
	import Prefooter from './Prefooter.svelte';
</script>

<main>
	<Hero />
	<section class="md:mx-20 lg:mx-40 xl:mx-60">
		<article class="md:grid grid-cols-2 gap-5">
			<div>
				<h2>HI!</h2>
				<h3>MY NAME IS EMILIE SCHULTZ</h3>
				<h4>I'M A MULTIMEDIADESIGN STUDENT WITH SPECIAL A FLAIR FOR UX & UI DESIGN...</h4>
			</div>
			<div class="flex justify-center">
				<img class="w-80" src="src/img/tegning.png" alt="" />
			</div>
		</article>
	</section>
	<section class="sectiontwo">
		<article class="md:px-20 lg:px-40 xl:px-60 py-10 px-1">
			<h2 class="mb-5 md:mb-10">WALL OF SKILLS</h2>
			<div class="md:grid grid-cols-3 gap-10">
				<div class="pb-6">
					<h4>HEJ</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, nam.</p>
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
					<h4>HEJ</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, nam.</p>
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
</main>

<style>
	.sectiontwo {
		background-color: var(--grey-color);
	}

	p {
		max-width: 60ch;
	}
</style>
