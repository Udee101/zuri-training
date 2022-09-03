<template>
	<div class="col-lg-6 p2">
		<full-time></full-time>
	</div>

	<div class="col-lg-6 p2">
		<part-time></part-time>
	</div>
</template>

<script>
	import FullTime from "@/components/FullTime.vue";
	import PartTime from "@/components/PartTime.vue";
	export default {
		name: "Program-structure",
		components: {
			FullTime,
			PartTime,
		},
	};
</script>

<style>
	.move {
		display: none;
	}
	.time-structure {
		width: 100%;
		background: #1b1a20 !important;
		color: #fff;
		padding: 64px 45px !important;
		border-radius: 65px;
		box-shadow: 0px 30px 45px 28px #ffe2d872;
		box-sizing: border-box;
		margin-bottom: 20px;
	}
	.time-structure .head {
		font-size: 2.17em;
		font-weight: 500;
	}
	.time-structure .title {
		font-size: 1.15em;
		font-weight: 500;
		margin: 0;
	}
	.time-structure ul {
		padding-left: 16px;
	}
	.hour-glass {
		width: 25%;
		display: flex;
		float: right;
		margin-top: -100px;
	}
	.time {
		width: 45%;
		display: flex;
		float: right;
		margin-top: -120px;
	}

	@media screen and (min-width: 700px) {
		.hour-glass {
			width: 18%;
			margin-top: -140px;
		}
		.time {
			width: 28%;
			margin-top: -140px;
		}
	}

	@media screen and (min-width: 900px) {
		.time-structure {
			height: 790px !important;
		}
		.hour-glass {
			width: 26%;
			display: flex;
			float: right;
			margin-top: -130px;
		}
		.time {
			width: 46%;
			display: flex;
			float: right;
			margin-top: -120px;
		}
	}

	@media screen and (min-width: 1024px) {
		.time-structure {
			width: 93%;
			margin: auto;
		}
	}

	@media screen and (min-width: 1200px) {
		.move {
			display: flex;
		}
		.move img {
			position: absolute;
			margin-left: -90px;
			margin-top: 220px;
		}
		.time-structure {
			width: 95%;
			margin: auto;
		}
		.hour-glass {
			width: 20%;
			margin-top: -130px;
		}
		.time {
			width: 40%;
			margin-top: -120px;
		}
	}
</style>