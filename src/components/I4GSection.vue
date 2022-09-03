<template>
	<div class="section-2-container">
		<div class="i4g-text d-flex pt-3 pb-2 ps-2 pe-2 text-uppercase">
			<p class="pt-3">
				Ingressive for Good was launched in July 2020 with No dollar in
				donation...
			</p>
		</div>

		<div class="i4g-img">
			<div class="i4g-img-main d-flex justify-content-center">
				<img src="@/assets/ingresive.jpg" alt="" />
			</div>
		</div>
		<div class="i4g-end-text">
			<p class="text-center pb-1">
				to help increase the earning power of African youths by providing them
				with tech skills, community, tools, resources, and jobs...
				<span
					><a href="https://ingressive.org/i4g=in-2021/" target="blank"
						>Read More</a
					></span
				>
			</p>
		</div>
	</div>
</template>

<script>
	export default {
		name: "i4g-section",
	};
</script>

<style scoped>
	.i4g-text {
		text-align: center;
		font-size: 1.25em;
		font-weight: 500;
		line-height: 130%;
	}
	.i4g-img {
		padding: 16px 10px;
	}
	.i4g-img-main {
		margin: auto;
	}
	.i4g-img-main img {
		width: 52% !important;
		mix-blend-mode: darken;
	}
	.i4g-end-text {
		padding: 16px 10px;
	}
	.i4g-end-text p {
		font-size: 1.1em;
		line-height: 130% !important;
	}
	.i4g-end-text span a {
		color: #43b97f;
		cursor: pointer;
	}

	@media screen and (min-width: 700px) {
		.i4g-img-main img {
			width: 42% !important;
		}
		.i4g-text {
			font-size: 1.5em;
			line-height: 130%;
			color: #1b1a20;
		}
		.i4g-text p {
			padding: 0 !important;
		}
		.i4g-end-text {
			padding: 16px 10px;
		}
		.i4g-end-text p {
			text-align: right !important;
			font-size: 1.1em;
			line-height: 130% !important;
			margin: 0 !important;
		}
	}

	@media screen and (min-width: 900px) {
		.section-2-container {
			display: flex;
			justify-content: space-between;
			align-items: center;
		}
		.i4g-img-main img {
			width: 50% !important;
		}
		.i4g-text {
			width: 55%;
			text-align: left !important;
			font-size: 1.15em;
		}
		.i4g-img-main {
			width: 100%;
		}
		.i4g-img-main img {
			width: 100% !important;
		}
		.i4g-end-text {
			width: 55%;
		}
		.i4g-end-text p {
			font-size: 1.1em;
		}
	}

	@media screen and (min-width: 1200px) {
		.i4g-img-main img {
			width: 100% !important;
		}
		.i4g-text {
			width: 48%;
			font-size: 1.5em;
		}
		.i4g-end-text {
			width: 50%;
		}
		.i4g-end-text p {
			font-size: 1.5em;
		}
	}
</style>