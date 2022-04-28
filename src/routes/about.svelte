<script>
	import Prefooter from './Prefooter.svelte';
	import Header from './Header.svelte';
</script>

<Header />
<main>
	<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-20">
		<h1 class="slide-in-top-side mb-1">ABOUT ME</h1>
		<article class="slide-in-bottom-side">
			<h3>Multimediadesign student with a flair for UX and UI design.</h3>
			<p class="pt-2">Hey, my name is Emilie Schultz and i'm 22 years old!</p>
			<div class="md:grid grid-cols-2 mt-5">
				<div class="pt-5 md:pr-8">
					<h4>Studies</h4>
					<p>
						I study multimediadesign at Copenhagen School of Technology and Design and expect to
						take a top-up bachelors degree (same school) after finishing the 4th semester of the
						multimediadesign education.
					</p>
				</div>
				<div class="pt-5">
					<h4>Work ethics</h4>
					<p>
						I have had many different, mostly service-related, jobs since the age of 13, and through
						these i've generated a very natural and flexible approach to people as well as tasks.
						Furthermore I have had a lot of experience with working in busy environments with short
						deadlines through for example my work in COWI A/S, where I was a Piccoline.
					</p>
				</div>
				<div class="pt-5 md:pr-8">
					<h4>Lets get personal</h4>
					<p>
						Many people around me would describe me as a smiling, moodbomb of a person and friend. I
						love being social and share fun experiences with my friends, and I thrive to create a
						positive environment around myself and the ones I'm with. I love listening to and
						sharing music with friends as well as going to concerts - and my best days and nights
						have and will always include music! I would describe myself as a very structured and
						punctual person while still loving to explore new possibilities and being spontaneous
						once in a while!
					</p>
					<p class="pt-5">
						I have always loved to travel and experience the world with my family, friends and by
						myself - this is why this little paragraph is included. I've seen and learned about the
						world and i've met many different and great cultures around it... I also feel like i've
						improved my spoken english by communicating with many different nationalities - a skill
						that I find usefull every single day. A travel to mention was my 2,5 month trip to New
						Zealand, Australia, Fiji and Hong-Kong with two friends, where we explored the nature
						and cities: sleeping under the nightsky in the Outback, walking on glaciers, horseback
						riding in the valleys, sightseeing the big towers of the cities and canoeing down
						rivers... Just amazing to experience the world and learn from it every day!
					</p>
				</div>
				<img class="pt-5" src="about1.jpg" alt="" />
			</div>
		</article>
	</section>
	<Prefooter knap1="PROJECTS" link1="/projects" knap2="CONTACT" link2="/contact" />
</main>

<style>
	/* img {
		border-radius: 50%;
	} */
</style>
