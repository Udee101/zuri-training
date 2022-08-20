<template>
	<button>
		<img :src="imgsrc" alt="" class="p-0 m-0" />
		{{ value }}
	</button>
</template>

<script>
	export default {
		name: "Button-label",
		props: {
			value: {
				type: String,
				default: "Label",
			},
			imgsrc: {
				type: String,
				default: "",
			},
		},
	};
</script>

<style scoped>
</style>