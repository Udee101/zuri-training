<template>
	<div class="section-1-wrapper">
		<div class="lady1 d-flex align-items-center">
			<img src="@/assets/lady1.jpg" alt="" class="d-flex" />
		</div>

		<div class="hero-texts">
			<hero-texts></hero-texts>

			<div class="enroll-btn d-flex justify-content-center">
				<a href="#"
					><Button
						class="rounded-pill pt-2 pb-2 ps-4 pe-4 m-o"
						value="Enroll Now"
				/></a>
			</div>
			<div class="wire d-flex justify-content-end m-auto">
				<img src="@/assets/section1wire.svg" alt="" />
			</div>

			<img src="@/assets/maleface.svg" alt="" class="maleface" width="100%" />
		</div>

		<div class="guy1 d-flex">
			<img src="@/assets/male1.jpg" alt="" width="100%" />
		</div>
	</div>
</template>

<script>
	import HeroTexts from "@/components/HeroTexts.vue";
	import Button from "@/components/Button.vue";
	export default {
		name: "Hero-section",
		components: {
			HeroTexts,
			Button,
		},
	};
</script>

<style>
	.section1 {
		font-family: "Graphik" !important;
		max-width: 1440px !important;
		width: 90% !important;
	}
	.lady1 {
		width: 100% !important;
		mix-blend-mode: darken !important;
	}
	.lady1 img {
		width: 100% !important;
		margin: auto;
	}
	.enroll-btn a button {
		font-size: 1.2em;
		background-color: #e7332b !important;
		color: #fff;
		border: none;
		cursor: pointer;
	}
	.wire {
		width: 64% !important;
	}
	.wire img {
		width: 22% !important;
	}
	.maleface {
		display: none;
	}
	.guy1 {
		display: none;
	}

	@media screen and (min-width: 700px) {
		.lady1 {
			width: 75% !important;
			height: 47%;
			display: flex;
			margin: auto;
			margin-bottom: 0 !important;
		}
		.lady1 img {
			width: 100%;
			margin: auto;
		}
		.wire {
			width: 70% !important;
		}
		.wire img {
			width: 25% !important;
			margin-right: 70px;
		}
		.maleface {
			display: block;
			position: absolute;
			width: 55px;
			margin-left: 40px;
			margin-top: -150px;
		}
	}
	@media screen and (min-width: 900px) {
		.lady1 {
			height: 54%;
		}
		.wire {
			width: 65% !important;
		}
		.wire img {
			width: 16% !important;
			margin-right: 70px;
		}
	}

	@media screen and (min-width: 1200px) {
		.section-1-wrapper {
			display: flex !important;
			justify-content: space-between;
			padding-top: 50px !important;
		}
		.guy1 {
			width: 65%;
			margin: auto !important;
		}
		.guy1 img {
			display: block !important;
			width: 100%;
			mix-blend-mode: darken;
		}
		.lady1 {
			height: 100%;
			width: 65% !important;
		}
		.hero-texts {
			width: 100%;
		}
		.wire {
			width: 80% !important;
		}
		.wire img {
			width: 24% !important;
			margin-right: 60px;
		}
	}
</style>