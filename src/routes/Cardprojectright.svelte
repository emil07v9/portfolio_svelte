<script>
	export let title;
	export let src;
	export let type;
	export let link;
	import { page } from '$app/stores';
</script>

<section class="md:grid grid-cols-2 grid-rows-1 gap-5">
	<img class="col-start-2 row-start-1" {src} alt="" />
	<div class="md:grid grid-rows-3 grid-cols-1 col-start-1 row-start-1">
		<h3>{title}</h3>
		<div>
			<div class="badge flex space-x-2">
				<hr class="flex self-center" />
				<p>{type}</p>
			</div>
		</div>
		<div class="flex justify-end p-1">
			<a sveltekit:prefetch href={link}
				><button class="flex justify-center zoom"><img class="pil" src="gåtil.svg" alt="" /></button
				></a
			>
		</div>
	</div>
</section>

<style>
	.brød {
		padding-top: 10px;
	}
	hr {
		width: 30px;
		background-color: var(--nav-color);
		height: 2px;
		padding-left: 10px;
	}

	.zoom {
		transition: transform 0.2s; /* Animation */
		margin: 0 auto;
	}

	.zoom:hover {
		transform: scale(
			1.2
		); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
	}

	button {
		height: 60px;
		width: 60px;
	}

	button:hover {
		border: solid 1px var(--nav-color);
		background-color: white !important;
	}

	button:hover {
		background-color: var(--nav-color);
		color: white;
	}

	.pil {
		width: 40px;
	}
</style>
