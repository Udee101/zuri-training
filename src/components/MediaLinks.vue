<template>
	<div class="foot-links d-flex">
		<div class="foot-logo d-flex pt-4">
			<a href="#"></a><img src="@/assets/logo.svg" alt="" />
		</div>
		<div class="d-flex pt-4">
			<div class="d-flex media-links">
				<a href=""><img src="@/assets/facebook.svg" alt="" /></a>
				<a href=""><img src="@/assets/linkd.svg" alt="" /></a>
				<a href=""><img src="@/assets/twitter.svg" alt="" /></a>
				<a href=""><img src="@/assets/youtube.svg" alt="" /></a>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: "Media-links",
	};
</script>

<style scoped>
	.foot-links {
		flex-wrap: wrap;
		justify-content: center;
	}
	.media-links a {
		margin-right: 10px;
	}

	@media screen and (min-width: 700px) {
		.foot-links {
			justify-content: space-between;
		}
	}
</style>