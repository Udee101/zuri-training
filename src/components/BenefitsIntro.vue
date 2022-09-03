<template>
	<div class="wire2 ps-5 d-flex justify-content-end">
		<img src="@/assets/section5wire.svg" alt="" class="m-auto" />
	</div>
	<p class="start">We will help you get started</p>
	<p class="high">High quality training with hands-on practice</p>
	<p class="tasks">
		We give you weekly tasks, ranging from easy to complex, as you progress from
		stage to stage; making it to the final stage means you are now ready to
		continue learning and growing independently.
	</p>

	<div class="enroll-btn1">
		<a href="#"><Button value="Enroll Now" /></a>
	</div>
</template>

<script>
	import Button from "@/components/Button.vue";
	export default {
		name: "Benefits-intro",
		components: {
			Button,
		},
	};
</script>

<style scoped>
	.wire2 img {
		width: 18%;
	}
	.start {
		font-size: 1.1em;
		margin: 0;
	}
	.high {
		font-size: 1.9em;
		font-weight: 500;
		line-height: 130% !important;
	}
	.tasks {
		font-size: 1.18em;
		line-height: 130%;
		margin-top: 30px;
		margin-bottom: 30px;
	}
	.enroll-btn1 a button {
		font-size: 1.2em;
		background-color: #fff;
		color: #e7332b;
		border: none;
		padding: 5px 25px;
		margin: 0;
		border-radius: 25px;
	}

	@media screen and (min-width: 900px) {
		.wire2 img {
			width: 20%;
			margin-left: 500px !important;
		}
	}

	@media screen and (min-width: 1200px) {
		.wire2 {
			margin: auto;
			width: 50%;
		}
		.wire2 img {
			width: 50%;
		}
		.high {
			font-size: 2.5em;
		}
		.tasks {
			width: 72%;
			font-size: 1.15em;
		}
	}
</style>