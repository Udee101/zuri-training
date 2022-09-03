<template>
	<div class="scope">
		<p class="head">Scope Of Program</p>
		<p class="sub-head">
			Here is the list of areas that will be explored in the training.
		</p>
	</div>
</template>

<script>
	export default {
		name: "Scope-intro",
	};
</script>

<style scoped>
	.scope {
		max-width: 1440px;
	}
	.scope .head {
		color: #e7332b;
		font-size: 1.15em;
		line-height: 130%;
		margin: 0;
	}
	.scope .sub-head {
		font-size: 1.55em;
		font-weight: 600;
		line-height: 130%;
	}

	@media screen and (min-width: 700px) {
		.scope {
			width: 95%;
			margin: auto;
		}
		.scope .sub-head {
			width: 65%;
			font-size: 1.5em;
			line-height: 130%;
			margin: 0;
		}
	}

	@media screen and (min-width: 900px) {
		.scope .head {
			font-size: 1.2em;
		}
		.scope .sub-head {
			font-size: 2em;
			width: 100%;
		}
	}

	@media screen and (min-width: 1200px) {
		.scope .head {
			font-size: 1.5em;
		}
		.scope .sub-head {
			font-size: 2.5em;
			width: 50%;
		}
	}
</style>