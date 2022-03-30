<script>
	import Prefooter from './Prefooter.svelte';
</script>

<section class="md:mx-20 lg:mx-40 xl:mx-60 mt-20">
	<div class="slide-in-top-side">
		<h1>KONTAKT</h1>
		<div class="flex gap-5">
			<hr class="flex self-center" />
			<h3>Har du spørgsmål eller vil du i kontakt?</h3>
		</div>
	</div>
	<article class="slide-in-bottom-side">
		<h2 class="mt-10">Sådan kan jeg kontaktes</h2>
		<article class="sm:grid grid-cols-3">
			<div class="flex gap-2 info">
				<img class="mail" src="/img/mail.svg" alt="" />
				<div>
					<h3>Email</h3>
					<a href="mailto:emilie@webschultz.dk">emilie@webschultz</a>
					<a class="block pt-1" href="mailto:emil07v9@stud.kea.dk">emil07v9@stud.kea.dk</a>
				</div>
			</div>
			<div class="flex gap-2 info">
				<img class="mobil" src="/img/mobil.svg" alt="" />
				<div>
					<h3>Mobil</h3>
					<a href="tel:42423796">+45 42423796</a>
				</div>
			</div>
			<div class="flex gap-2 info">
				<img class="social" src="/img/social.svg" alt="" />
				<div>
					<h3>LinkedIn</h3>
					<a href="www.linkedin.com/in/emiliekempelschultz">
						<img class="linked" src="/img/LI-in-Bug.png" alt="" /></a
					>
				</div>
			</div>
		</article>
	</article>
</section>

<Prefooter knap1="PROJECTS" knap2="ABOUT" />
<div class="flex justify-end mt-10">
	<a class="rotate-180 mr-5" href="#"><img class="puls" src="/img/pil.svg" alt="" /></a>
</div>

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
