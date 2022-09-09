<template>
	<div>
		<nav-bar class="sticky-top"></nav-bar>

		<section class="section1 d-flex align-itmes-center pt-3 m-auto">
			<hero-section></hero-section>
		</section>

		<section class="section2 m-auto pt-4" id="about">
			<div>
				<hr class="m-3 md-0" />
			</div>
			<i-4-g-section></i-4-g-section>
			<div>
				<hr class="m-3 md-0" />
			</div>
		</section>

		<why-us-section></why-us-section>

		<section class="section4">
			<div class="section4-container pt-5 pb-0 ps-3 pe-3">
				<div class="container-wrapper">
					<div class="benefits-container">
						<benefits-container></benefits-container>
					</div>

					<div class="section4-img">
						<div>
							<img src="@/assets/section5-image.png" alt="" />
						</div>
					</div>
				</div>
				<div class="section4-dot">
					<img src="@/assets/dotsection5.svg" alt="" />
				</div>
			</div>
		</section>

		<section class="section5">
			<div class="section5-container" id="stack">
				<scope-container></scope-container>
			</div>
		</section>

		<section class="section6 m-auto">
			<div>
				<hr class="m-3 md-0" />
			</div>
			<div class="section6-container" id="faq">
				<faq-section></faq-section>
			</div>
		</section>

		<div class="got-q text-center pt-5 pb-5">
			<p class="mb-0 pb-2">Still got questions?</p>
			<div class="tweet-btn d-flex justify-content-center">
				<a href="https://twitter.com/thezuriteam" target="blank">
					<Button
						class="rounded-pill ps-2 pe-4 m-0 border-0"
						value="Tweet them at us"
						:imgsrc="require('@/assets/twitter.svg')"
					/>
				</a>
			</div>
		</div>

		<section class="section7">
			<div>
				<hr class="m-3 md-0" />
			</div>
			<prog-structure-section></prog-structure-section>

			<div>
				<img src="@/assets/circle.png" alt="" class="d-flex circle" />
			</div>
		</section>

		<section class="section8">
			<div class="circle2">
				<img src="@/assets/circle.png" alt="" class="d-flex" />
			</div>

			<get-started></get-started>
		</section>

		<zuri-footer></zuri-footer>
	</div>
</template>

<script>
	import NavBar from "@/components/NavBar.vue";
	import HeroSection from "@/views/HeroSection.vue";
	import I4GSection from "@/views/I4GSection.vue";
	import WhyUsSection from "@/views/WhyUsSection.vue";
	import Button from "@/components/Button.vue";
	import BenefitsContainer from "@/views/BenefitsContainer.vue";
	import ScopeContainer from "@/views/ScopeContainer.vue";
	import FaqSection from "@/views/FaqSection.vue";
	import ProgStructureSection from "@/views/ProgStructureSection.vue";
	import GetStarted from "@/components/GetStarted.vue";
	import ZuriFooter from "@/components/ZuriFooter.vue";

	export default {
		name: "ZuriTrainingPage",
		components: {
			NavBar,
			HeroSection,
			I4GSection,
			Button,
			WhyUsSection,
			BenefitsContainer,
			ScopeContainer,
			FaqSection,
			ProgStructureSection,
			GetStarted,
			ZuriFooter,
		},
		data() {
			return {
				isShown: true,
				isShown2: true,
			};
		},
	};
</script>

<style>
	.section2 {
		font-family: "Graphik" !important;
		max-width: 1440px !important;
		width: 90% !important;
	}
	.section2 hr {
		opacity: 20%;
		border: 0.2px solid #514949;
	}
	.section4 {
		font-family: "Graphik" !important;
		background: #e7332b;
		margin-top: 149px;
		color: #fff;
		width: 100%;
		max-width: 100%;
		margin: auto;
		margin-top: 170px;
		overflow-x: hidden !important;
	}
	.section4-img {
		width: 100%;
		margin-top: 10px;
	}
	.section4-img img {
		width: 100%;
	}
	.section4-dot {
		width: 100%;
	}
	.section4-dot img {
		margin: 35px 20px;
		width: 12%;
	}
	.section5 {
		background: linear-gradient(
			180deg,
			rgba(255, 244, 240, 0),
			#fffaf8d4 17.19%,
			#fff6f3 84.37%,
			rgba(255, 244, 240, 0)
		) !important;
		font-family: "Graphik" !important;
	}
	.section5-container {
		padding: 70px 20px 0;
		width: 100% !important;
		margin: auto !important;
	}
	.section6-container {
		font-family: "Graphik" !important;
		width: 100%;
		padding: 20px;
		max-width: 1440px !important;
		margin: auto !important;
	}
	.got-q p {
		font-size: 1.1em;
	}
	.tweet-btn a {
		text-decoration: none;
	}
	.tweet-btn a button {
		font-size: 1.16em;
		display: flex;
		align-items: center;
		background-color: #e7332b !important;
		color: #fff;
		cursor: pointer;
	}
	.tweet-btn a img {
		width: 50px;
	}
	.circle {
		width: 35%;
		float: right;
		margin-top: -110px;
	}
	.circle2 {
		display: none;
	}
	@media screen and (min-width: 700px) {
		.section4-container {
			width: 90%;
			margin: auto;
		}
		.got-q {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 100%;
		}
		.got-q p {
			margin-right: 15px;
		}
		.tweet-btn a button {
			font-size: 1.1em;
			display: flex;
			align-items: center;
			text-decoration: none !important;
		}
		.tweet-btn a {
			text-decoration: none !important;
		}
		.tweet-btn a img {
			width: 40px;
		}
		.circle {
			width: 15%;
			margin-top: -110px;
		}
	}

	@media screen and (min-width: 800px) {
		.circle2 {
			display: block;
			margin: 50px;
		}
		.circle2 img {
			position: absolute;
			width: 9%;
			float: left;
			margin-top: -80px;
		}
	}

	@media screen and (min-width: 900px) {
		.section2 {
			padding-top: 0 !important;
		}
		.section6-container {
			padding: 45px 30px 20px;
		}
		.circle2 img {
			margin-top: -90px;
		}
	}

	@media screen and (min-width: 1200px) {
		.container-wrapper {
			display: flex;
		}
		.benefits-container {
			width: 42%;
		}
		.section4-dot img {
			margin: 35px 0;
		}
		.section6-container {
			padding-top: 65px;
		}
		.circle {
			width: 13%;
			margin-top: -125px;
			margin-right: 85px;
		}
		.circle2 img {
			margin-top: -160px;
			margin-left: 90px;
		}
	}
</style>