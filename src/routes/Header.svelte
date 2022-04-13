<script>
	import { page } from '$app/stores';
</script>

<header>
	<!-- Mobil -->
	<article id="mobil">
		<input type="checkbox" id="active" />
		<label for="active" class="menu-btn"><span /></label>
		<label for="active" class="close" />
		<div class="wrapper">
			<ul>
				<li class:active={$page.url.pathname === '/projektgalleri'}>
					<a sveltekit:prefetch href="/projektgalleri">PROJECTS</a>
				</li>
				<li class:active={$page.url.pathname === '/about'}>
					<a sveltekit:prefetch href="/about">ABOUT</a>
				</li>
				<li class:active={$page.url.pathname === '/kontakt'}>
					<a sveltekit:prefetch href="/kontakt">CONTACT</a>
				</li>
			</ul>
		</div>
	</article>
	<!-- Desktop -->
	<article id="desktop">
		<figure class:active={$page.url.pathname === '/'}>
			<a sveltekit:prefetch href="/"><img src="logo.svg" alt="" /></a>
		</figure>
		<nav>
			<ul class="mt-5">
				<li class:active={$page.url.pathname === '/projektgalleri'}>
					<a sveltekit:prefetch href="/projektgalleri">PROJECTS</a>
				</li>
				<li class:active={$page.url.pathname === '/about'}>
					<a sveltekit:prefetch href="/about">ABOUT</a>
				</li>
				<li class:active={$page.url.pathname === '/kontakt'}>
					<a sveltekit:prefetch href="/kontakt">CONTACT</a>
				</li>
			</ul>
		</nav>
	</article>
</header>

<style>
	header {
		cursor: url(cursor.svg);
	}
	a {
		color: var(--nav-color);
	}
	img {
		width: 90px;
		padding-left: 1rem;
	}

	header {
		margin-bottom: 30px;
	}

	header + * {
		padding-top: 100px;
	}

	.wrapper {
		position: fixed;
		top: 0;
		/*left: -100%;*/
		right: -100%;
		height: 100%;
		width: 100%;
		z-index: 100;
		background: var(--beige-color);
		/*background: linear-gradient(90deg, #f92c78, #4114a1);*/
		/* background: linear-gradient(375deg, #1cc7d0, #2ede98); */
		/* background: linear-gradient(-45deg, #e3eefe 0%, #efddfb 100%);*/
		transition: all 0.6s ease-in-out;
	}

	.wrapper li {
		margin-right: 4rem !important;
	}

	#active:checked ~ .wrapper {
		/*left: 0;*/
		right: 0;
	}

	.menu-btn {
		position: absolute;
		z-index: 200;
		right: 20px;
		/*left: 20px; */
		top: 20px;
		height: 50px;
		width: 50px;
		text-align: center;
		line-height: 50px;
		border-radius: 50%;
		font-size: 20px;
		cursor: pointer;
		transition: all 0.3s ease-in-out;
		background: var(--nav-color);
	}

	.menu-btn span,
	.menu-btn:before,
	.menu-btn:after {
		content: '';
		position: absolute;
		top: calc(50% - 1px);
		left: 25%;
		width: 40%;
		border-bottom: 2px solid white;
		transition: transform 0.6s cubic-bezier(0.215, 0.61, 0.355, 1);
		height: 2px;
		width: 50%;
		background: white;
	}
	.menu-btn:before {
		transform: translateY(-8px);
	}
	.menu-btn:after {
		transform: translateY(8px);
	}

	.close {
		z-index: 3;
		width: 100%;
		height: 100%;
		pointer-events: none;
		transition: background 0.6s;
	}

	/* closing animation */
	#active:checked + .menu-btn span {
		transform: scaleX(0);
	}
	#active:checked + .menu-btn:before {
		transform: rotate(45deg);
		border-color: white;
	}

	#active:checked + .menu-btn:after {
		transform: rotate(-45deg);
		border-color: white;
	}

	.wrapper ul li {
		height: 10%;
		margin: 15px 0;
		color: white;
	}
	.wrapper ul li a {
		text-decoration: none;
		font-size: 30px;
		font-weight: 500;
		padding: 5px 30px;
		color: var(--nav-color);
		border-radius: 50px;
		position: absolute;
		line-height: 50px;
		margin: 5px 30px;
		opacity: 0;
		transition: all 0.3s ease;
		transition: transform 0.6s cubic-bezier(0.215, 0.61, 0.355, 1);
	}
	.wrapper ul {
		position: absolute;
		top: 60%;
		left: 43%;
		text-align: center;
		height: 90%;
		transform: translate(-50%, -50%);
		list-style: none;
		text-align: center;
	}

	.wrapper ul li a:hover {
		color: white !important;
	}

	.wrapper ul li a:after {
		position: absolute;
		content: '';
		background: var(--nav-color);
		/*background: linear-gradient(#14ffe9, #ffeb3b, #ff00e0);*/
		/*background: linear-gradient(375deg, #1cc7d0, #2ede98);*/
		width: 100%;
		height: 100%;
		left: 0;
		top: 0;
		border-radius: 50px;
		transform: scaleY(0);
		z-index: -1;
		transition: transform 0.3s ease;
	}

	.wrapper ul li a:hover:after {
		transform: scaleY(1);
	}
	.wrapper ul li a:hover {
		color: black;
	}
	input[type='checkbox'] {
		display: none !important;
	}

	#active:checked ~ .wrapper ul li a {
		opacity: 1;
	}
	.wrapper ul li a {
		transition: opacity 1.2s, transform 1.2s cubic-bezier(0.215, 0.61, 0.355, 1);
		transform: translateX(100px);
	}
	#active:checked ~ .wrapper ul li a {
		transform: none;
		transition-timing-function: ease, cubic-bezier(0.1, 1.3, 0.3, 1); /* easeOutBackを緩めた感じ */
		transition-delay: 0.6s;
		transform: translateX(-100px);
	}

	nav {
		display: none;
	}

	@media (min-width: 700px) {
		.wrapper,
		label {
			display: none;
		}

		nav {
			display: block;
			padding-right: 2rem;
		}

		ul {
			display: flex;
		}

		article {
			display: flex;
			justify-content: space-between;
			align-items: center;
		}

		li {
			padding: 1rem;
		}
	}
</style>
