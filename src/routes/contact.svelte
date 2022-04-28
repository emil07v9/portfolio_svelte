<script>
	import Prefooter from './Prefooter.svelte';
	import Header from './Header.svelte';
</script>

<Header />
<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-20">
	<div class="slide-in-top-side">
		<h1>CONTACT</h1>
		<div class="flex">
			<hr class="mr-3 flex mt-5 md:mt-7" />
			<h3>Do you have any questions or do you want to contact me?</h3>
		</div>
	</div>
	<article class="slide-in-bottom-side">
		<h3 class="mt-10">This i how you can reach me...</h3>
		<article class="sm:grid grid-cols-3">
			<div class="flex info">
				<img class="mail mr-3" src="mail.svg" alt="" />
				<div>
					<h4>Email</h4>
					<a href="mailto:emilie@webschultz.dk">emilie@webschultz</a>
					<a class="block pt-1" href="mailto:emil07v9@stud.kea.dk">emil07v9@stud.kea.dk</a>
				</div>
			</div>
			<div class="flex info">
				<img class="mobil mr-3" src="mobil.svg" alt="" />
				<div>
					<h4>Phone</h4>
					<a href="tel:42423796">+45 42423796</a>
				</div>
			</div>
			<div class="flex info">
				<img class="social mr-3" src="social.svg" alt="" />
				<div>
					<h4>LinkedIn</h4>
					<a target="_blank" href="https://www.linkedin.com/in/emiliekempelschultz/">
						<img class="linked" src="LI-in-Bug.png" alt="" /></a
					>
				</div>
			</div>
		</article>
	</article>
</section>

<Prefooter knap1="PROJECTS" link1="/projects" knap2="ABOUT" link2="/about" />

<style>
	.info {
		padding-top: 20px;
	}
	hr {
		width: 30px;
		background-color: var(--nav-color);
		height: 2px;
		padding-left: 10px;
	}
	h1 {
		margin-block: 0;
	}

	.linked {
		width: 40px;
	}

	.mobil {
		width: 40px;
	}

	.mail {
		width: 40px;
	}

	.social {
		width: 50px;
	}

	h2 {
		padding-bottom: 30px;
	}
</style>
