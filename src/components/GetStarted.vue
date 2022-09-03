<template>
	<div class="section8-container rounded-5">
		<div class="img1">
			<img src="@/assets/round.svg" alt="" />
		</div>
		<div class="img2">
			<img src="@/assets/bend1.svg" alt="" />
		</div>
		<div class="text-center text-light started">
			<p class="head">Get Started</p>
			<p class="desc">Break into the tech industry like a Pro</p>
			<div class="enroll-btn d-flex justify-content-center">
				<a href="#"
					><Button
						value="Enroll Now"
						class="rounded-pill pt-2 pb-2 ps-4 pe-4 m-0"
				/></a>
			</div>
		</div>
		<div class="d-flex">
			<div class="img3 d-flex">
				<img src="@/assets/curve2.svg" alt="" />
			</div>
			<div class="img4 d-flex justify-content-end">
				<img src="@/assets/mains.png" alt="" />
			</div>
		</div>
	</div>
</template>

<script>
	import Button from "@/components/Button.vue";
	export default {
		name: "Get-started",
		components: {
			Button,
		},
	};
</script>

<style scoped>
	.section8-container {
		font-family: "Graphik" !important;
		width: 90%;
		max-width: 1440px !important;
		background: #e7332b;
		margin-top: 75px !important;
		margin: auto;
	}
	.img1 img {
		width: 20%;
		position: absolute;
		left: 15%;
		margin-top: 28px;
	}
	.img2 img {
		width: 22%;
		position: absolute;
		right: 5%;
	}
	.img3 img {
		width: 120%;
	}
	.img4 {
		width: 180%;
	}
	.img4 img {
		display: flex;
		width: 20%;
	}
	.started {
		margin: auto;
		padding: 100px 50px 0;
		width: 100%;
	}
	.started .head {
		font-size: 1.2em;
	}
	.started .desc {
		font-size: 1.9em;
		line-height: 130%;
		font-weight: 500;
		padding-bottom: 35px;
	}
	.started .enroll-btn button {
		font-size: 1.2em;
		background-color: #fff !important;
		color: #e7332b;
		border: none;
		cursor: pointer;
	}

	@media screen and (min-width: 700px) {
		.section8-container {
			margin-top: 120px;
		}
		.started .desc {
			width: 70%;
			margin: auto;
			font-size: 2.2em;
		}
		.img1 img {
			width: 15%;
			left: 15%;
			margin-top: 70px;
		}
	}

	@media screen and (min-width: 900px) {
		.section8-container {
			margin-top: 150px !important;
		}
		.started .desc {
			font-size: 3em;
		}
		.img2 img {
			width: 12%;
		}
	}

	@media screen and (min-width: 1200px) {
		.section8-container {
			margin-top: 220px !important;
		}
		.started {
			padding: 80px 50px 0;
		}
		.started .desc {
			font-size: 3.5em;
			width: 50%;
			margin: auto;
		}
		.img1 img {
			width: 12%;
			left: 15%;
			margin-top: 68px;
		}
		.img3 img {
			width: 160%;
		}
		.img4 img {
			width: 15%;
		}
	}
</style>