<template>
	<zuri-training-page></zuri-training-page>
</template>

<script>
	import ZuriTrainingPage from "@/views/ZuriTrainingPage.vue";
	export default {
		name: "App",
		components: {
			ZuriTrainingPage,
		},
	};
</script>

<style>
	* {
		box-sizing: border-box;
	}
	#app {
		font-family: "Graphik" !important;
		background: rgb(255, 253, 245);
	}
	body {
		display: block;
		margin: 0 !important;
		font-family: "Graphik" !important;
		box-sizing: border-box;
	}
</style>
