<template>
	<faq-intro></faq-intro>
	<div class="faqs mt-5 pt-5 m-auto">
		<FAQ></FAQ>
	</div>
</template>

<script>
	import FAQ from "@/components/FAQ.vue";
	import FaqIntro from "@/components/FaqIntro.vue";
	export default {
		name: "Faq-section",
		components: {
			FaqIntro,
			FAQ,
		},
	};
</script>

<style>
	.faqs {
		width: 100%;
	}

	@media screen and (min-width: 700px) {
		.faqs {
			width: 95% !important;
		}
	}

	@media screen and (min-width: 900px) {
		.faqs {
			margin: auto !important;
			width: 80% !important;
		}
	}
</style>