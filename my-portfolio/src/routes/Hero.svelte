<article>
	<div class="mx-4 sm:grid sm:grid-cols-2 sm:grid-rows-1 gap-8">
		<h1 class="sm:col-start-2 mb-0 flex justify-center">/FOLIO <br /> 2K22</h1>
		<div class="grid grid-cols-3 grid-rows-3 sm:col-start-1 sm:row-start-1 sm:mt-10">
			<img
				class="col-start-1 col-span-2 row-start-1 row-span-2 lg:flex lg:justify-center"
				src="/src/img/hero.png"
				alt=""
			/>
			<img
				class="rotate-90 col-start-2 col-span-2 row-start-2 row-span-2 lg:flex lg:justify-center"
				src="/src/img/hero.png"
				alt=""
			/>
		</div>
	</div>
	<div class="flex justify-center mt-10">
		<a href="#"><img class="knap_ned" src="src/img/pil.svg" alt="" /></a>
	</div>
</article>

<style>
	article {
		background-color: var(--beige-color);
		width: 100vw;
		height: 95vh;
	}

	h1 {
		color: var(--nav-color);
		font-size: 100px;
	}

	img {
		width: 250px;
		height: 150px;
		padding-top: 0;
	}

	.knap_ned {
		width: 70px;
		display: flex;
		justify-self: center;
	}

	button {
		height: 80px;
		width: 80px;
	}

	button:hover {
		background-color: var(--beige-color);
		color: var(--nav-color);
	}

	@media (min-width: 640px) {
		article {
			height: 80vh;
		}
	}
</style>
