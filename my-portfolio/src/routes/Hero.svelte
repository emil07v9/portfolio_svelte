<div id="bg_image">
	<div id="text">
		<p class="slide-left">EMILIE KEMPEL SCHULTZ</p>
		<div class="typing-demo1">
			<h1>PORTFOLIO</h1>
		</div>
	</div>
	<a href="#"><img src="/src/img/pilned.svg" alt="" /></a>
</div>

<style>
	#bg_image {
		background-image: url('src/img/hero.png');
		position: relative;
		width: 100vw;
		height: 90vh;
		background-size: cover;
		background-repeat: no-repeat;
	}

	#text {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}

	img {
		position: absolute;
		color: black;
		top: 85%;
		left: 50%;
	}

	.typing-demo1 {
		--w: 42ch;
		width: 0ch;
		animation: typing 3s steps(22) forwards, blink 0.2s step-end alternate;
		white-space: nowrap;
		overflow: hidden;
		border-right: 3px solid;
		/* font-family: 'BiauKai'; */
		/* font-size: 3em; */
		animation-delay: 0.5s;
	}

	p {
		text-align: center;
	}

	/* .slide-left {
		-webkit-animation: slide-left 2s cubic-bezier(0.25, 0.46, 0.45, 0.94) 3s both;
		animation: slide-left 2s cubic-bezier(0.25, 0.46, 0.45, 0.94) 3s both;
	} */

	/* Animation h1 */
	@keyframes typing {
		to {
			width: var(--w);
		}
	}

	@keyframes blink {
		50% {
			border-color: transparent;
		}
	}
	@keyframes caret {
		50% {
			border-color: transparent;
		}
	}

	/* Animation p-tekst */
	/* @-webkit-keyframes slide-left {
		0% {
			-webkit-transform: translateX(0);
			transform: translateX(0);
		}
		100% {
			-webkit-transform: translateX(-100px);
			transform: translateX(-100px);
		}
	}
	@keyframes slide-left {
		0% {
			-webkit-transform: translateX(0);
			transform: translateX(0);
		}
		100% {
			-webkit-transform: translateX(-100px);
			transform: translateX(-100px);
		}
	} */
</style>
