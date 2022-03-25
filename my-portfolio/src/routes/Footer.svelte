<footer>
	<section>
		<h3>KONTAKT</h3>
		<ul>
			<li>Tlf. +45 42423796</li>
			<li>Privat Email <a href="mailto:emilie@webschultz.dk">emilie@webschultz</a></li>
			<li>Skole Email <a href="mailto:emil07v9@stud.kea.dk">emil07v9@stud.kea.dk</a></li>
		</ul>
	</section>
	<section>
		<h3>SOCIAL</h3>
		<ul>
			<li><a href=""> <img src="/src/img/LI-in-Bug.png" alt="" /></a></li>
		</ul>
	</section>
	<section>
		<h3>PORTFOLIO</h3>
		<ul>
			<li>Lavet af Emilie Schultz</li>
			<li>Bygget I SvelteKit</li>
		</ul>
	</section>
</footer>

<style>
	a {
		color: var(--nav-color);
	}
	footer {
		background: var(--beige-color);
		padding: 1rem;
	}

	li {
		list-style: none;
		padding-top: 0.5rem;
	}

	ul {
		padding-bottom: 2rem;
	}

	h3 {
		color: var(--footer-h3);
	}

	img {
		width: 40px;
	}

	@media (min-width: 600px) {
		footer {
			display: grid;
			grid-template-columns: repeat(3, 1fr);
		}

		section {
			justify-self: center;
		}
	}
</style>
