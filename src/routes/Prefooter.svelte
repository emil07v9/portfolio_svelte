<script>
	export let knap1;
	export let knap2;
	export let link1;
	export let link2;
</script>

<section class="md:mx-20 lg:mx-40 xl:mx-60">
	<div class="flex justify-center">
		<h4 class="self-center text-right">IT DOESN'T <br /> HAVE TO END HERE...</h4>
		<hr class="rotate-90 self-center" />
		<p>
			Email me at <a href="mailto:emil07v9@stud.kea.dk">emilie@webschultz.dk</a> <br /> or learn more
			here
		</p>
	</div>
	<div class="flex justify-end pr-10 sm:pr-20 md:pr-40 lg:pr-60">
		<img src="pilned.svg" alt="" />
	</div>
	<div class="flex justify-center">
		<a class="pr-2" sveltekit:prefetch href={link1}><button>{knap1}</button></a>
		<a class="pl-2" sveltekit:prefetch href={link2}><button>{knap2}</button></a>
	</div>
</section>

<style>
	hr {
		width: 80px;
		background-color: var(--nav-color);
		height: 2px;
	}
	section {
		margin-top: 10rem;
	}

	h4 {
		padding-right: 0;
	}

	p {
		padding-left: 0;
	}

	img {
		width: 60px;
	}
</style>
