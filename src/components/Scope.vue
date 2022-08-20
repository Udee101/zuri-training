<template>
	<div>
		<p class="head">{{ header }}</p>
		<div class="icons mt-4 mb-4 d-flex">
			<img class="img1" :src="img_src1" alt="" />
			<img class="img2" :src="img_src2" alt="" />
			<img class="img3" :src="img_src3" alt="" />
			<img class="img4" :src="img_src4" alt="" />
		</div>

		<p class="desc pt-3 pb-2">{{ description }}</p>
	</div>
</template>

<script>
	export default {
		name: "Program-scope",
		props: {
			header: {
				type: String,
				default: "",
			},
			img_src1: {
				type: String,
				default: "",
			},
			img_src2: {
				type: String,
				default: "",
			},
			img_src3: {
				type: String,
				default: "",
			},
			img_src4: {
				type: String,
				default: "",
			},
			description: {
				type: String,
				default: "",
			},
		},
	};
</script>

<style scoped>
</style>