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
	@font-face {
		font-display: fallback;
		font-family: Graphik;
		font-style: normal;
		font-weight: 400;
		src: url(/static/media/Graphik-Regular.42a9b7733ff5f4bc9df8.woff2)
			format("woff2");
		unicode-range: U+0020-007f;
	}

	@font-face {
		font-display: fallback;
		font-family: Graphik;
		font-style: normal;
		font-weight: 500;
		src: url(/static/media/Graphik-Medium.2b31c0c333758d818c25.woff2)
			format("woff2");
		unicode-range: U+0020-007f;
	}

	@font-face {
		font-display: fallback;
		font-family: Graphik;
		font-style: normal;
		font-weight: 600;
		src: url(/static/media/Graphik-Semibold.f9277a68f8dbabfbba24.woff2)
			format("woff2");
		unicode-range: U+0020-007f;
	}
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
		font-family: Graphik !important;
		/* background: #fffefe !important; */
	}
</style>
