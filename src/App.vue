<template>
	<zuri-training></zuri-training>
</template>

<script>
	import ZuriTraining from "@/views/ZuriTraining.vue";
	export default {
		name: "App",
		components: {
			ZuriTraining,
		},
	};
</script>

<style>
	@import "./assets/style.css";
	* {
		box-sizing: border-box;
	}
	#app {
		font-family: Graphik !important;
		background: rgb(255, 253, 245);
	}
	body {
		display: block;
		margin: 0 !important;
		font-family: "Graphik" !important;
		/* background: #fffefe !important; */
	}
</style>
