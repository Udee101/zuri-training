<template>
	<footer>
		<media-links></media-links>

		<div class="pt-4 pb-4 foot-bottom">
			<other-links></other-links>

			<hr class="bottom-line" />

			<div class="copy">
				<p>&copy; 2022 Zuri Training</p>
			</div>
		</div>
	</footer>
</template>

<script>
	import MediaLinks from "@/components/MediaLinks.vue";
	import OtherLinks from "@/components/OtherLinks.vue";
	export default {
		name: "Zuri-footer",
		components: {
			MediaLinks,
			OtherLinks,
		},
	};
</script>

<style>
	footer {
		font-family: "Graphik" !important;
		width: 90%;
		max-width: 1440px;
		margin: auto;
		padding-top: 90px;
	}
	.copy {
		text-align: center;
		font-size: 1em;
	}

	@media screen and (min-width: 700px) {
		.foot-bottom {
			display: flex;
			justify-content: space-between;
		}
		.bottom-line {
			display: none !important;
		}
		.copy {
			position: absolute;
			float: left;
			margin-top: 38px;
		}
	}
</style>