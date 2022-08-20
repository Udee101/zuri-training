<template>
	<div>
		<img :src="img_link" alt="" class="why-us-img" />
		<p class="num">{{ number }}</p>
		<p class="head">{{ heading }}</p>
		<p class="details">{{ details }}</p>
	</div>
</template>

<script>
	export default {
		name: "Why-us",
		props: {
			img_link: String,
			number: String,
			heading: String,
			details: String,
		},
	};
</script>

<style scoped>
</style>