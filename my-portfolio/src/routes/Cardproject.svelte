<script>
	export let title;
	export let text;
	export let src;
</script>

<a href="#">
	<section id="zoom">
		<img {src} alt="" />
		<div>
			<h4>{title}</h4>
			<p>
				{text}
			</p>
		</div>
	</section>
</a>

<style>
	section {
		border-radius: 12px;
		background-color: var(--beige-color);
		width: 22rem;
	}

	@media (min-width: 400px) {
		section {
			display: grid;
			grid-template-columns: 1fr minmax(0, 1000px) 1fr;
		}
	}

	img {
		border-radius: 12px;
	}

	div {
		padding-block: 15px;
		padding-inline: 10px;
		align-content: center;
	}

	#zoom {
		transition: transform 0.2s; /* Animation */
		/* width: 200px;
		height: 200px; */
		/* margin: 0 auto; */
		margin-block: 4rem;
	}

	#zoom:hover {
		transform: scale(
			1.1
		); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
	}
</style>
