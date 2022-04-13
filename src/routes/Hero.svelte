<article>
	<div class="mt-20 lg:mt-20">
		<div class="grid grid-cols-3 md:grid-cols-6">
			<h5 class="hidden header">
				EMILIE SCHULTZ <hr />
				COPENHAGEN, DENMARK
			</h5>
			<div class="col-start-1 col-span-3 mx-5 md:col-start-3 md:col-span-2 gap-10">
				<img class="slide-in-bottom myDIV w-full sm:h-96 md:h-full" src="profil1.png" alt="" />
				<h1 class="slide-in-top">PORTFOLIO</h1>
			</div>
			<div class="grid grid-rows-3 md:col-span-2">
				<div class="flex md:row-start-3 mx-5">
					<hr class="mr-3 self-center md:self-end mb-2 slide-in-left" />
					<h5 class="self-center md:self-end typing-demo1">DIGITAL DESIGNER</h5>
				</div>
			</div>
		</div>
		<div class="flex justify-center lg:mt-5 sm:mt-10 sm:pt-10">
			<a class="slide-in-bottom" href="#"><img class="puls" src="pil.svg" alt="" /></a>
		</div>
	</div>
</article>

<style>
	hr {
		display: flex;
		justify-self: center;
	}
	h1 {
		color: var(--nav-color);
	}
	.typing-demo1 {
		--w: 18ch;
		width: 0ch;
		animation: typing 2.5s steps(24) forwards, blink 0.5s step-end infinite alternate;
		white-space: nowrap;
		overflow: hidden;
		border-right: 3px solid;
		animation-delay: 0.5s;
	}

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
	@keyframes slide-in-left {
		0% {
			-webkit-transform: translateX(-50px);
			transform: translateX(-50px);
			opacity: 0;
		}
		100% {
			-webkit-transform: translateX(0);
			transform: translateX(0);
			opacity: 1;
		}
	}

	hr {
		width: 30px;
		background-color: var(--nav-color);
		height: 2px;
		padding-left: 10px;
	}

	.myDIV {
		position: relative;
	}

	h1 {
		position: absolute;
		top: 25%;
		left: 10%;
	}

	@keyframes slide-in-right {
		0% {
			-webkit-transform: translateX(1000px);
			transform: translateX(1000px);
			opacity: 0;
		}
		100% {
			-webkit-transform: translateX(0);
			transform: translateX(0);
			opacity: 1;
		}
	}

	.puls {
		animation-name: puls_kf;
		animation-duration: 0.7s;
		animation-iteration-count: infinite;
		animation-timing-function: linear;
		animation-direction: alternate;
	}

	@keyframes puls_kf {
		0% {
			transform: scale(0.9);
		}

		100% {
			transform: scale(1);
		}
	}

	@media (min-width: 500px) {
		h1 {
			top: 25%;
			left: 15%;
		}

		hr {
			place-self: end;
			margin-bottom: 12px;
		}
	}

	@media (min-width: 700px) {
		.slide-in-left {
			-webkit-animation: slide-in-left 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
			animation: slide-in-left 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
		}
		@-webkit-keyframes slide-in-left {
			0% {
				-webkit-transform: translateX(-50px);
				transform: translateX(-50px);
				opacity: 0;
			}
			100% {
				-webkit-transform: translateX(0);
				transform: translateX(0);
				opacity: 1;
			}
		}
		.slide-in-bottom {
			-webkit-animation: slide-in-bottom 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
			animation: slide-in-bottom 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
			animation-iteration-count: 1;
		}
		@-webkit-keyframes slide-in-bottom {
			0% {
				-webkit-transform: translateY(90px);
				transform: translateY(90px);
				opacity: 0;
			}
			100% {
				-webkit-transform: translateY(0);
				transform: translateY(0);
				opacity: 1;
			}
		}

		.slide-in-top {
			-webkit-animation: slide-in-top 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
			animation: slide-in-top 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
		}
		@-webkit-keyframes slide-in-top {
			0% {
				-webkit-transform: translateY(-90px);
				transform: translateY(-90px);
				opacity: 0;
			}
			100% {
				-webkit-transform: translateY(0);
				transform: translateY(0);
				opacity: 1;
			}
		}
		@keyframes slide-in-top {
			0% {
				-webkit-transform: translateY(-90px);
				transform: translateY(-90px);
				opacity: 0;
			}
			100% {
				-webkit-transform: translateY(0);
				transform: translateY(0);
				opacity: 1;
			}
		}
	}

	@media (min-width: 768px) {
		.header {
			position: fixed;
			top: 25%;
			width: 100vh;
			transform-origin: top left;
			transform: rotate(90deg) translateY(-100%);
			display: flex;
			gap: 5px;
		}
	}
	@media (min-width: 800px) {
		h1 {
			top: 25%;
			left: 20%;
		}

		.header {
			top: 20%;
		}
	}

	@media (min-width: 1000px) {
		h1 {
			top: 18%;
			left: 25%;
		}
	}
</style>
