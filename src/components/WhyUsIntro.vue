<template>
	<div class="why-us d-flex p-3 mt-0 mb-4 ms-2 me-2" id="why-us">
		<div>
			<div class="wire3 d-flex justify-content-center">
				<img src="@/assets/section3wire.svg" alt="" />
			</div>
			<div class="why-us-flex">
				<div class="why-us-text">
					<p class="why-us-q mb-0">Why Zuri Training?</p>
					<p class="why-us-intro">
						Here at Zuri, you gain access to enough knowledge to introduce and
						aid your success in the tech industry.
					</p>
				</div>

				<div class="star3 justify-content-center">
					<img src="@/assets/Star.jpg" alt="" />
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: "WhyUsIntro",
	};
</script>

<style>
	.why-us-text .why-us-q {
		color: #e7332b;
		font-size: 1.1em;
		line-height: 130%;
	}
	.why-us-intro {
		font-size: 1.59em;
		font-weight: 500;
		line-height: 130%;
	}
	.wire3 img {
		width: 15% !important;
	}
	.star3 {
		display: none;
	}

	@media screen and (min-width: 900px) {
		.why-us {
			width: 90%;
		}
		.why-us-text .why-us-q {
			color: #e7332b;
			font-size: 1.1em;
			line-height: 130%;
		}
		.why-us-intro {
			width: 85%;
			font-size: 1.8em;
			line-height: 130%;
		}
		.wire3 img {
			width: 10% !important;
			margin-left: -200px;
		}
		.why-us-flex {
			margin: auto;
			width: 95%;
			display: flex;
			justify-content: space-around;
		}
		.star3 {
			mix-blend-mode: darken;
			display: flex;
			width: 80%;
		}
		.star3 img {
			width: 95%;
			height: 85%;
		}
	}

	@media screen and (min-width: 1024px) {
		.why-us-intro {
			width: 88%;
			font-size: 1.8em;
			line-height: 130%;
		}
	}

	@media screen and (min-width: 1200px) {
		.why-us-text .why-us-q {
			font-size: 1.5em;
		}
		.why-us-intro {
			width: 85%;
			font-size: 2.5em;
		}
		.wire3 img {
			width: 10% !important;
			margin-left: -220px;
		}
		.why-us-flex {
			margin: auto;
			width: 85%;
		}
		.why-us-flex img {
			width: 200px;
		}
	}
</style>