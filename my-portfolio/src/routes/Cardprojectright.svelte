<script>
	export let title;
	export let text;
	export let src;
	export let type;
	import { page } from '$app/stores';
</script>

<section class="md:grid grid-cols-2 gap-5">
	<div>
		<h2>{title}</h2>
		<div>
			<div class="badge flex space-x-2">
				<hr class="flex self-center" />
				<p>{type}</p>
			</div>
		</div>
		<p>{text}</p>
	</div>
	<img {src} alt="" />
</section>

<style>
	hr {
		width: 30px;
		background-color: var(--nav-color);
		height: 2px;
		padding-left: 10px;
	}
</style>
