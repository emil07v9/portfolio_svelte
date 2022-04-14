<footer class="p-1 md:p-0">
	<section>
		<h4>CONTACT</h4>
		<ul>
			<li>Phone <a href="tel:42423796">+45 42423796</a></li>
			<li>Private email <a href="mailto:emilie@webschultz.dk">emilie@webschultz</a></li>
			<li>School email <a href="mailto:emil07v9@stud.kea.dk">emil07v9@stud.kea.dk</a></li>
		</ul>
	</section>
	<section>
		<h4>SOCIAL</h4>
		<ul>
			<li>
				<a target="_blank" href="https://www.linkedin.com/in/emiliekempelschultz/">
					<img src="LI-in-Bug.png" alt="" /></a
				>
			</li>
		</ul>
	</section>
	<section>
		<h4>PORTFOLIO</h4>
		<ul>
			<li>Made by Emilie Schultz</li>
			<li>Build in SvelteKit</li>
		</ul>
	</section>
</footer>

<style>
	a {
		color: var(--nav-color);
	}
	footer {
		background: var(--beige-color);
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
