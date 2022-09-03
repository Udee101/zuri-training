<template>
	<p class="hero-small text-center">And now your search has ended...</p>
	<p class="hero-large text-center pt-2 mb-0">
		Gain Knowledge to help you scale through the tech industry for free.
	</p>
	<div class="line d-flex justify-content-end">
		<img src="@/assets/line.svg" alt="" width="33%" />
	</div>

	<p class="hero-medium pb-4 text-center fw-normal">
		A basic introduction to software development and product design aimed at
		complete beginners, which anyone can join.
	</p>
</template>

<script>
	export default {
		name: "Hero-text",
	};
</script>

<style scoped>
	.hero-texts .hero-small {
		font-size: 1.1em;
		color: #e7332b;
		line-height: 24% !important;
	}
	.hero-texts .hero-large {
		color: #1b1a20 !important;
		font-size: 1.8em;
		font-weight: 500;
		line-height: 32px;
	}
	.line {
		margin: 0 32px 28px -20px;
	}
	.hero-texts .hero-medium {
		font-size: 1.02em;
		color: #1b1a20 !important;
		line-height: 22px;
	}
	@media screen and (min-width: 700px) {
		.hero-texts .hero-small {
			font-size: 1.1em;
			color: #e7332b;
			line-height: 24% !important;
		}
		.hero-texts .hero-large {
			color: #1b1a20 !important;
			font-size: 2.3em;
			line-height: 120%;
		}
		.hero-texts .hero-medium {
			width: 60%;
			margin: auto;
			font-size: 1.1em;
			color: #1b1a20 !important;
			line-height: 22px;
		}
	}
	@media screen and (min-width: 900px) {
		.hero-texts .hero-medium {
			width: 65%;
			margin: auto;
			margin-bottom: 10px;
		}
	}
	@media screen and (min-width: 1024px) {
		.hero-texts .hero-large {
			font-size: 3em;
		}
		.line {
			width: 82%;
		}
	}
	@media screen and (min-width: 1200px) {
		.hero-texts .hero-medium {
			width: 75%;
		}
	}
</style>