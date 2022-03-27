<script>
	import Prefooter from './Prefooter.svelte';
</script>

<section class="md:mx-20 lg:mx-40 xl:mx-60">
	<h1>KONTAKT</h1>
	<h3>Har du spørgsmål eller vil du i kontakt?</h3>

	<h2 class="mt-10">Sådan kan jeg kontaktes</h2>
	<article>
		<div>
			<h3>Email</h3>
			<a href="mailto:emilie@webschultz.dk">emilie@webschultz</a>
			<a class="block" href="mailto:emil07v9@stud.kea.dk">emil07v9@stud.kea.dk</a>
		</div>
		<div>
			<h3>Mobil</h3>
			<a href="tel:42423796">+45 42423796</a>
		</div>
		<div>
			<h3>LinkedIn</h3>
			<a href=""> <img src="/src/img/LI-in-Bug.png" alt="" /></a>
		</div>
	</article>
</section>

<Prefooter knap1="PROJEKTER" knap2="OM MIG" />

<style>
	h1 {
		margin-block: 0;
	}

	img {
		width: 40px;
	}

	h3 {
		padding-top: 20px;
	}
</style>
