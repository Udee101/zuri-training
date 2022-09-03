<template>
	<div class="d-flex faq-wire justify-content-start mb-0">
		<img src="@/assets/section7wire.svg" alt="" width="20%" class="ms-5" />
	</div>

	<div class="faq-head text-center">
		<p class="faq-q m-0">Got Questions?</p>
		<p class="faq-intro">Frequently Asked Questions</p>
	</div>
</template>

<script>
	export default {
		name: "Faq-intro",
	};
</script>

<style scoped>
	.faq-q {
		font-size: 1.1em;
		color: #e7332b;
		line-height: 130%;
	}
	.faq-intro {
		font-size: 1.5em;
		font-weight: 500;
	}

	@media screen and (min-width: 900px) {
		.faq-wire {
			width: 52%;
			position: absolute;
			margin-left: 50px;
			margin-top: -20px;
		}
		.faq-q {
			font-size: 1.2em;
		}
		.faq-intro {
			font-size: 2em;
		}
	}

	@media screen and (min-width: 1200px) {
		.faq-q {
			font-size: 1.5em;
		}
		.faq-intro {
			font-size: 2.5em;
		}
	}
</style>