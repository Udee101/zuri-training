<template>
	<why-us-intro></why-us-intro>
	<section class="section3">
		<div class="box-container pt-2 m-auto row">
			<div class="col-md-4 pb-4">
				<why-us-box
					class="box1"
					:img_link="require('@/assets/curve1.png')"
					number="01"
					heading="Fully Remote"
					details="100% online classes available to anyone in the world."
				></why-us-box>
			</div>

			<div class="col-md-4 pb-4">
				<why-us-box
					class="box2"
					:img_link="require('@/assets/curve.svg')"
					number="02"
					heading="Hands-on Experience"
					details="We don't teach you theory, we show you how to build things."
				></why-us-box>
			</div>

			<div class="col-md-4 pb-4">
				<why-us-box
					class="box2"
					:img_link="require('@/assets/curve3.svg')"
					number="03"
					heading="Collaborative learning"
					details="We connect you with like minds to grow together."
				></why-us-box>
			</div>
		</div>

		<div class="box-container pt-2 m-auto row">
			<div class="col-md-4 pb-4">
				<why-us-box
					class="box2"
					:img_link="require('@/assets/curve4.svg')"
					number="04"
					heading="Real-life Projects"
					details="We give CV worthy projects to help you hit the ground."
				></why-us-box>
			</div>

			<div class="col-md-4 pb-4">
				<why-us-box
					class="box2"
					:img_link="require('@/assets/curve5.svg')"
					number="05"
					heading="Beginner Friendly"
					details="We provide step-by-step procedures on how to get things done."
				></why-us-box>
			</div>

			<div class="col-md-4 pb-4">
				<why-us-box
					class="box2"
					:img_link="require('@/assets/curve6.svg')"
					number="06"
					heading="In-program Mentorship"
					details="During and after the program you have access to experience seniors."
				></why-us-box>
			</div>
		</div>
	</section>
</template>

<script>
	import WhyUsIntro from "@/components/WhyUsIntro.vue";
	import WhyUsBox from "@/components/WhyUsBox.vue";
	export default {
		name: "WhyUsSection",
		components: {
			WhyUsIntro,
			WhyUsBox,
		},
	};
</script>

<style>
	.section3 {
		background: linear-gradient(
			180deg,
			rgba(255, 244, 240, 0),
			#fff4f098 17.19%,
			#fff4f0a9 84.37%,
			rgba(255, 244, 240, 0)
		) !important;
		font-family: "Graphik" !important;
		width: 100% !important;
		margin: auto !important;
	}
	.box-container {
		width: 95% !important;
		max-width: 1440px !important;
	}
	.box1 {
		/* height: 400px; */
		padding: 54px 52px 63px 40px;
		color: #fff;
		background: #e7332b !important;
		border-radius: 18px !important;
		transition: transform 0.3s ease !important;
		box-shadow: 0px 10px 20px 0 #ffd1c0;
		transition: 0.5s ease;
	}
	.box1:hover {
		transform: translate(0, -10px);
	}
	.box2 {
		/* height: 400px; */
		padding: 54px 52px 63px 40px;
		color: #000;
		background: #fff !important;
		border-radius: 18px !important;
		transition: transform 0.3s ease !important;
		box-shadow: 0px 10px 20px 0 #ffd9cc;
		transition: 0.5s ease;
	}
	.box2:hover {
		transform: translate(0, -10px);
	}
	.box1 .why-us-img,
	.box2 .why-us-img {
		display: flex;
		float: right !important;
		width: 42%;
		margin-top: -55px;
		margin-right: -53px;
	}
	.box1 .num,
	.box2 .num {
		font-size: 2.7em;
		font-weight: 500;
	}
	.box1 .head,
	.box2 .head {
		font-size: 1.8em;
		font-weight: 500;
		width: 160px;
	}
	.box1 .details,
	.box2 .details {
		font-size: 1.1em;
		padding-top: 3px;
	}

	@media screen and (min-width: 800px) {
		.box1 {
			width: 100%;
			height: 420px;
		}
		.box2 {
			width: 100%;
			height: 420px;
		}
	}

	@media screen and (min-width: 900px) {
		.box1 {
			width: 100%;
			height: 400px;
		}
		.box2 {
			width: 100%;
			height: 400px;
		}
	}
</style>