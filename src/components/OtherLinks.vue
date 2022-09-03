<template>
	<div class="bottom-links pb-4 pt-4">
		<p class="mb-4 i4g">
			<a href="https://ingressive.org">Ingressive For Good</a>
		</p>
		<p class="privacy">
			<a href="https://training.zuri.team/privacy">Privacy Policy</a>
		</p>
	</div>
</template>

<script>
	export default {
		name: "Other-links",
	};
</script>

<style scoped>
	.bottom-links {
		text-align: center;
	}
	.bottom-links p a {
		font-size: 1em;
		text-decoration: none;
		color: #1b1a20;
	}

	@media screen and (min-width: 700px) {
		.bottom-links {
			width: 100%;
			display: flex;
			justify-content: flex-end;
			float: right !important;
			margin-top: 15px;
		}
		.bottom-links .i4g {
			position: absolute;
			float: right;
		}
		.bottom-links .privacy {
			position: absolute;
			float: left;
			margin-right: 160px;
		}
	}
</style>