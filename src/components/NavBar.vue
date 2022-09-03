<template>
	<nav>
		<div class="wrapper">
			<div class="logo">
				<a href="https://training.zuri.team"
					><img src="@/assets/logo.svg" alt=""
				/></a>
			</div>
			<div class="nav-links">
				<a href="#about">About</a>
				<a href="#why-us">Why Us?</a>
				<a href="#stack">Stacks Covered</a>
				<a href="#faq">FAQs</a>
			</div>

			<div class="enroll d-flex">
				<img src="@/assets/thumbs.png" alt="" />
				<a href="#"><Button value="Enroll Now" class="rounded-pill" /></a>
			</div>
		</div>
	</nav>
</template>

<script>
	import Button from "@/components/Button.vue";

	export default {
		name: "Nav-bar",
		components: {
			Button,
		},
	};
</script>

<style scoped>
	nav {
		font-family: Graphik !important;
		max-width: 100%;
		padding: 15px;
		overflow: hidden;
		background: rgb(255, 253, 245);
	}
	.wrapper {
		display: inline-flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: space-between;
		width: 100%;
		padding: 10px 5px;
		margin: 0 2px;
		margin: auto;
	}
	.logo img {
		padding: 15px 0;
		width: 150px;
	}
	.nav-links {
		display: none;
	}
	.nav-links a {
		color: #585757 !important;
	}
	.enroll {
		display: inline;
		align-items: center;
	}
	.enroll img {
		background-color: #e7332b !important;
		border-radius: 50%;
		margin-left: -42px !important;
		padding: 10px !important;
		position: absolute !important;
		width: 60px !important;
	}
	.enroll a button {
		font-size: 1.2em;
		background-color: #e7332b !important;
		color: #fff;
		border: none;
		padding: 10px 20px;
		margin: 0;
	}

	@media screen and (min-width: 800px) {
		.wrapper {
			display: flex;
			justify-content: space-between;
			padding: 0 20px;
		}
		.nav-links {
			display: none;
		}
		.logo a img {
			width: 300px;
		}
	}

	@media screen and (min-width: 1024px) {
		.logo img {
			width: 250px;
			padding: 15px;
		}
		nav {
			width: 100%;
			padding: 10px;
		}
		.wrapper {
			justify-content: space-between;
			width: 90%;
			padding: 5px;
			margin: auto;
		}
		.nav-links {
			width: 400px;
			display: flex;
			justify-content: flex-end;
			align-items: center;
			margin: 0 30px 0 0;
		}
		.nav-links a {
			text-decoration: none;
			font-size: 0.9em;
			margin: 0 0.5em;
			padding: 0 1em 0 0;
		}
		.enroll img {
			margin-left: -50px !important;
			width: 70px !important;
		}
	}

	@media screen and (min-width: 1440px) {
		.logo img {
			width: 340px;
		}
		.nav-links {
			width: 550px;
			display: flex;
			justify-content: center;
			align-items: center;
			margin: 0 0 0 200px;
		}
		.nav-links a {
			text-decoration: none;
			font-size: 1.2em;
			margin: 0 0.7em;
			padding: 0 1em 0 0;
		}
		.wrapper {
			width: 95%;
			padding: 10px 40px;
		}
	}
</style>