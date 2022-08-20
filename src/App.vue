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
		font-family: Graphik;
		background: rgb(255, 253, 245);
	}
	body {
		display: block;
		margin: 0 !important;
		/* background: #fffefe !important; */
	}
</style>
