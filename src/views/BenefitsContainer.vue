<template>
	<benefits-intro></benefits-intro>

	<div class="container text-center d-flex">
		<div class="benefits">
			<benefits
				:img_src="require('@/assets/hand.svg')"
				value="Teamwork"
			></benefits>
		</div>

		<div class="benefits">
			<benefits
				:img_src="require('@/assets/mentor.svg')"
				value="Mentorship"
			></benefits>
		</div>

		<div class="benefits">
			<benefits
				:img_src="require('@/assets/practice.svg')"
				value="Practice"
			></benefits>
		</div>

		<div class="benefits">
			<benefits
				:img_src="require('@/assets/games.svg')"
				value="Fun & Games"
			></benefits>
		</div>
	</div>
</template>

<script>
	import Benefits from "@/components/Benefits.vue";
	import BenefitsIntro from "@/components/BenefitsIntro.vue";
	export default {
		name: "Benefits-container",
		components: {
			BenefitsIntro,
			Benefits,
		},
	};
</script>

<style scoped>
	.section4 .container {
		width: 100%;
		flex-flow: row wrap;
		margin-top: 28px;
		padding: 0;
	}
	.section4 .benefits {
		flex-basis: 50%;
		padding: 15px 5px 10px 5px;
	}

	@media screen and (min-width: 700px) {
		.section4 .container {
			width: 90%;
			justify-content: flex-start !important;
			align-items: left !important;
			margin-top: 28px;
			margin-left: 0 !important;
			padding: 0;
		}
		.section4 .benefits {
			flex-basis: 40%;
			padding: 15px 0px 10px 0;
			margin-right: 50px;
		}
	}

	@media screen and (min-width: 900px) {
		.section4 .benefits {
			flex-basis: 35%;
			padding: 15px 0 10px 0;
			margin-right: 100px;
		}
	}
	@media screen and (min-width: 1024px) {
		.section4 .benefits {
			flex-basis: 32%;
			padding: 15px 0px 10px 0;
			margin-right: 100px;
		}
	}

	@media screen and (min-width: 1200px) {
		.section4 .benefits {
			flex-basis: 45%;
			padding: 15px 0 10px 0;
			margin-right: 18px;
		}
	}
</style>