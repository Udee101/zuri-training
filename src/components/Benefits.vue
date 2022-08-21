<template>
	<div class="benefit-box d-flex text-center align-items-center">
		<img class="benefit-img" :src="img_src" alt="" />
		<p class="benefit-text">{{ value }}</p>
	</div>
</template>

<script>
	export default {
		name: "Benefit-box",
		props: {
			img_src: String,
			value: String,
		},
	};
</script>

<style scoped>
	.benefit-box {
		font-family: "Graphik" !important;
		padding: 11px 10px 12px;
		background: transparent;
		border: 2px solid #fff;
		border-radius: 50px;
	}
	.benefit-box .benefit-img {
		width: 25%;
		margin: 0 5px 0 3px;
	}
	.benefit-box .benefit-text {
		font-size: 0.9em;
		margin: 0 3px;
	}
</style>