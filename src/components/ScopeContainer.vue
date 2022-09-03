<template>
	<scope-intro></scope-intro>

	<div class="wire4 d-flex justify-content-center" width="100%">
		<img src="@/assets/section6.svg" alt="" />
	</div>

	<div class="scope-container row m-auto">
		<div class="col-md-4 pb-4">
			<scope
				:class="[isShown ? 'show' : '']"
				class="scope-box front-end"
				header="Frontend Development"
				:img_src1="require('@/assets/html.svg')"
				:img_src2="require('@/assets/css-3 logo.svg')"
				:img_src3="require('@/assets/javascript logo.svg')"
				description="This track deals with the aspect of your application that the users interact with. A front-end developer will be able to correctly interpret a given design to the user interface."
			></scope>
		</div>

		<div class="col-md-4 pb-4">
			<scope
				:class="[isShown ? 'show' : '']"
				class="scope-box back-end"
				header="Backend Development"
				:img_src1="require('@/assets/php2 logo.svg')"
				:img_src2="require('@/assets/python-4 logo.svg')"
				:img_src3="require('@/assets/javascript logo.svg')"
				description="This track deals with the aspect of the application the user does not directly interact with. It allows the frontend function either by running some back-end code or connecting to the database."
			></scope>
		</div>

		<div class="col-md-4 pb-4">
			<scope
				:class="[isShown && isShown2 ? 'show show2' : '']"
				class="scope-box design"
				header="Product Design"
				:img_src1="require('@/assets/adobe-xd logo.svg')"
				:img_src2="require('@/assets/Figma logo.svg')"
				description="This track deals with creating a graphic plan for an application. You will learn to convert project documentation into viewable and understandable graphic design for the developers to work with."
			></scope>
		</div>
	</div>

	<div class="scope-container row m-auto">
		<div class="col-md-4 pb-4">
			<scope
				:class="[isShown ? 'show' : '']"
				class="scope-box dev-ops"
				header="DevOPS"
				:img_src1="require('@/assets/Ubuntu logo.svg')"
				:img_src2="require('@/assets/Bash logo.svg')"
				:img_src3="require('@/assets/aws logo.svg')"
				description="The DevOps track is an extension of the backend track. It involves tools that'll allow the participant to deploy solutions for public use."
			></scope>
		</div>

		<div class="col-md-4 pb-4">
			<scope
				:class="[isShown ? 'show' : '']"
				class="scope-box full-stack"
				header="Fullstack Development"
				:img_src1="require('@/assets/html.svg')"
				:img_src2="require('@/assets/css-3 logo.svg')"
				:img_src3="require('@/assets/javascript logo.svg')"
				:img_src4="require('@/assets/python-4 logo.svg')"
				description="A combination of frontend, backend, and DevOps. This track will only be available to participants who have the time to dedicate to the training."
			></scope>
		</div>

		<div class="col-md-4 pb-4">
			<scope
				:class="[isShown ? 'show' : '']"
				class="scope-box frame-works"
				header="Frameworks"
				:img_src1="require('@/assets/Laravel logo.svg')"
				:img_src2="require('@/assets/React logo.svg')"
				:img_src3="require('@/assets/Django logo.svg')"
				description="During the program we will be exploring several useful frameworks to give you an edge in the industry and help you develop complex applications much faster."
			></scope>
		</div>
	</div>

	<div class="enroll-btn d-flex justify-content-center mt-5 mb-5">
		<a href="#"
			><Button class="rounded-pill pt-2 pb-2 ps-4 pe-4 m-0" value="Enroll Now"
		/></a>
	</div>
</template>

<script>
	import Button from "@/components/Button.vue";
	import Scope from "@/components/Scope.vue";
	import ScopeIntro from "@/components/ScopeIntro.vue";
	export default {
		name: "Scope-container",
		components: {
			Button,
			Scope,
			ScopeIntro,
		},
	};
</script>

<style>
	.wire4 img {
		width: 45%;
	}
	.scope-container {
		width: 100% !important;
		max-width: 1440px !important;
		overflow: hidden !important;
	}
	.scope-box {
		padding: 40px;
		color: #000;
		background: #fff !important;
		border-radius: 40px !important;
		transition: transform 0.3s ease !important;
		box-shadow: 0px 12px 15px 0 #ffe2d879;
		transition: 0.5s ease;
	}
	.scope-box .head {
		font-size: 1.25em;
		font-weight: 500;
	}
	.scope-box img {
		margin-right: 15px;
	}
	.show .img4 {
		display: none !important;
	}
	.show2 .img3 {
		display: none;
	}
	.scope-box .desc {
		font-size: 1em;
		line-height: 150%;
	}
	.front-end .img1,
	.front-end .img2,
	.full-stack .img1,
	.full-stack .img2 {
		width: 35px;
	}
	.front-end .img3,
	.full-stack .img3,
	.back-end .img3 {
		width: 46px;
	}
	.full-stack .img4,
	.back-end .img2,
	.design .img1 {
		width: 50px;
	}
	.back-end .img1 {
		width: 62px;
	}
	.design .img2 {
		width: 97px;
	}
	.dev-ops .img2,
	.frame-works .img2,
	.frame-works .img3 {
		width: 75px;
	}
	.dev-ops .img3,
	.frame-works .img1 {
		width: 60px;
	}
	.dev-ops .img1 {
		width: 100px;
	}
	.dev-ops .desc {
		margin-bottom: 44px;
	}
	.frame-works .desc {
		margin-bottom: 34px;
	}
	.design .desc,
	.front-end .desc {
		margin-bottom: 25px;
	}

	@media screen and (min-width: 700px) {
		.wire4 img {
			width: 12%;
			margin-top: -22px;
		}
	}

	@media screen and (min-width: 800px) {
		.scope-box {
			height: 520px;
		}
		.design .img1,
		.dev-ops .img1,
		.dev-ops .img2,
		.dev-ops .img3,
		.frame-works .img2,
		.frame-works .img3,
		.back-end .img1 {
			width: 42px;
		}
		.front-end .img1,
		.front-end .img2,
		.front-end .img3,
		.back-end .img3,
		.full-stack .img3 {
			width: 20%;
		}
		.full-stack .img1,
		.full-stack .img2 {
			width: 30px;
		}
		.design .img2 {
			width: 48%;
		}
	}

	@media screen and (min-width: 900px) {
		.scope-box {
			width: 100%;
			height: 500px;
			margin: auto !important;
		}
		.dev-ops .img1,
		.dev-ops .img2,
		.dev-ops .img3,
		.frame-works .img2,
		.frame-works .img3 {
			width: 75px;
		}
		.full-stack .img1,
		.full-stack .img2 {
			width: 51px;
		}
		.full-stack .img3,
		.back-end .img1 {
			width: 64px;
		}
	}

	@media screen and (min-width: 1200px) {
		.scope-box {
			height: 420px;
		}
	}
</style>