<template>
	<div class="section7-heading mt-5">
		<div class="m-0 wire7">
			<img src="@/assets/section7wire.svg" alt="" style="width: 20%" />
		</div>

		<div class="d-flex justify-content-end star">
			<img src="@/assets/Star1.svg" alt="" width="12%" />
		</div>

		<div class="text-center structure">
			<p class="heading m-0">Structure</p>
			<p class="sub-head">Program Structure</p>
			<p class="desc">
				There are 2 broad paths in this program based on your availability.
			</p>
		</div>
	</div>
</template>

<script>
	export default {
		name: "Structure-intro",
	};
</script>

<style scoped>
	.section7-heading {
		width: 100%;
		max-width: 1440px;
		margin: auto !important;
		padding: 10px 35px;
	}
	.section7 .star {
		margin-top: -60px;
	}
	.structure .heading {
		font-size: 1.17em;
		color: #e7332b;
	}
	.structure .sub-head {
		font-size: 1.57em;
		font-weight: 500;
	}

	@media screen and (min-width: 700px) {
		.structure .desc {
			font-size: 1.1em;
		}
	}

	@media screen and (min-width: 900px) {
		.section7-heading {
			width: 90%;
			margin: auto !important;
			padding: 0 35px 10px;
		}
		.wire7 img {
			position: absolute;
			margin-left: 50px;
			width: 12% !important;
		}
		.section7 .star {
			margin-top: 55px;
		}
		.structure .sub-head {
			font-size: 2em;
		}
	}

	@media screen and (min-width: 1200px) {
		.structure .heading {
			font-size: 1.5em;
		}
		.structure .sub-head {
			font-size: 2.5em;
		}
	}
</style>