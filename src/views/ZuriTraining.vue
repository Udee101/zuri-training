<template>
	<div>
		<nav-bar class="sticky-top"></nav-bar>

		<section class="section1 d-flex align-itmes-center pt-3 m-auto">
			<div class="section-1-wrapper">
				<div class="lady1 d-flex align-items-center">
					<img src="@/assets/lady1.jpg" alt="" class="d-flex" />
				</div>

				<div class="hero-texts">
					<p class="hero-small text-center">And now your search has ended...</p>
					<p class="hero-large text-center pt-2 mb-0 fw-semibold">
						Gain Knowledge to help you scale through the tech industry for free.
					</p>
					<div class="line d-flex justify-content-end">
						<img src="@/assets/line.svg" alt="" width="33%" />
					</div>

					<p class="hero-medium pb-4 text-center fw-normal">
						A basic introduction to software development and product design
						aimed at complete beginners, which anyone can join.
					</p>

					<div class="enroll-btn d-flex justify-content-center">
						<a href="#"
							><Button
								class="rounded-pill pt-2 pb-2 ps-4 pe-4 m-o"
								value="Enroll Now"
						/></a>
					</div>
					<div class="wire d-flex justify-content-end m-auto">
						<img src="@/assets/section1wire.svg" alt="" />
					</div>
				</div>

				<div class="guy1 d-flex">
					<img src="@/assets/male1.jpg" alt="" width="100%" />
				</div>
			</div>
		</section>

		<section class="section2 m-auto pt-4" id="about">
			<div>
				<hr class="m-3 md-0" />
			</div>
			<div class="section-2-container">
				<div
					class="i4g-text d-flex fw-semibold pt-3 pb-2 ps-2 pe-2 text-center text-uppercase"
				>
					<p class="pt-3">
						Ingressive for Good was launched in July 2020 with No dollar in
						donation...
					</p>
				</div>

				<div class="i4g-img">
					<div class="i4g-img-main d-flex justify-content-center">
						<img src="@/assets/ingresive.jpg" alt="" />
					</div>
				</div>
				<div class="i4g-end-text">
					<p class="text-center pb-1">
						to help increase the earning power of African youths by providing
						them with tech skills, community, tools, resources, and jobs...
						<span
							><a href="https://ingressive.org/i4g=in-2021/" target="blank"
								>Read More</a
							></span
						>
					</p>
				</div>
			</div>
			<div>
				<hr class="m-3 md-0" />
			</div>
		</section>

		<div class="why-us d-flex p-3 mt-0 mb-4 ms-2 me-2" id="why-us">
			<div>
				<div class="wire3 d-flex justify-content-center">
					<img src="@/assets/section3wire.svg" alt="" />
				</div>

				<div class="why-us-text">
					<p class="why-us-q mb-0">Why Zuri Training?</p>
					<p class="why-us-intro">
						Here at Zuri, you gain access to enough knowledge to introduce and
						aid your success in the tech industry.
					</p>
				</div>

				<div class="star3 justify-content-center">
					<img src="@/assets/Star.jpg" alt="" />
				</div>
			</div>
		</div>

		<section class="section3">
			<div class="box-container pt-2 m-auto row">
				<div class="col-lg-4 pb-4">
					<why-us-box
						class="box1"
						:img_link="require('@/assets/curve1.png')"
						number="01"
						heading="Fully Remote"
						details="100% online classes available to anyone in the world."
					></why-us-box>
				</div>

				<div class="col-lg-4 pb-4">
					<why-us-box
						class="box2"
						:img_link="require('@/assets/curve.svg')"
						number="02"
						heading="Hands-on Experience"
						details="We don't teach you theory, we show you how to build things."
					></why-us-box>
				</div>

				<div class="col-lg-4 pb-4">
					<why-us-box
						class="box2"
						:img_link="require('@/assets/curve3.svg')"
						number="03"
						heading="Collaborative learning"
						details="We connect you with like minds to grow together."
					></why-us-box>
				</div>
			</div>

			<div class="box-container pt-2 m-auto row">
				<div class="col-lg-4 pb-4">
					<why-us-box
						class="box2"
						:img_link="require('@/assets/curve4.svg')"
						number="04"
						heading="Real-life Projects"
						details="We give CV worthy projects to help you hit the ground."
					></why-us-box>
				</div>

				<div class="col-lg-4 pb-4">
					<why-us-box
						class="box2"
						:img_link="require('@/assets/curve5.svg')"
						number="05"
						heading="Beginner Friendly"
						details="We provide step-by-step procedures on how to get things done."
					></why-us-box>
				</div>

				<div class="col-lg-4 pb-4">
					<why-us-box
						class="box2"
						:img_link="require('@/assets/curve6.svg')"
						number="06"
						heading="In-program Mentorship"
						details="During and after the program you have access to experience seniors."
					></why-us-box>
				</div>
			</div>
		</section>

		<section class="section4">
			<div class="section4-container pt-5 pb-0 ps-3 pe-3">
				<div>
					<div class="wire2 ps-5 d-flex justify-content-end">
						<img src="@/assets/section5wire.svg" alt="" class="m-auto" />
					</div>
					<p class="start">We will help you get started</p>
					<p class="high">High quality training with hands-on practice</p>
					<p class="tasks">
						We give you weekly tasks, ranging from easy to complex, as you
						progress from stage to stage; making it to the final stage means you
						are now ready to continue learning and growing independently.
					</p>

					<div class="enroll-btn1">
						<a href="#"><Button value="Enroll Now" /></a>
					</div>

					<div class="container text-center d-flex">
						<div class="benefits">
							<benefits
								:img_src="require('@/assets/hand.svg')"
								value="Teamwork"
							></benefits>
						</div>

						<div class="benefits">
							<benefits
								:img_src="require('@/assets/mentor.svg')"
								value="Mentorship"
							></benefits>
						</div>

						<div class="benefits">
							<benefits
								:img_src="require('@/assets/practice.svg')"
								value="Practice"
							></benefits>
						</div>

						<div class="benefits">
							<benefits
								:img_src="require('@/assets/games.svg')"
								value="Fun & Games"
							></benefits>
						</div>
					</div>

					<div class="section4-img">
						<div>
							<img src="@/assets/section5-image.png" alt="" />
						</div>
					</div>
				</div>
				<div class="section4-dot">
					<img src="@/assets/dotsection5.svg" alt="" />
				</div>
			</div>
		</section>

		<section class="section5">
			<div class="section5-container" id="stack">
				<div class="scope">
					<p class="head">Scope Of Program</p>
					<p class="sub-head">
						Here is the list of areas that will be explored in the training.
					</p>
				</div>

				<div class="wire4 d-flex justify-content-center" width="100%">
					<img src="@/assets/section6.svg" alt="" />
				</div>

				<div class="scope-container row m-auto">
					<div class="col-lg-4 pb-4">
						<scope
							class="scope-box front-end"
							header="Frontend Development"
							:img_src1="require('@/assets/html.svg')"
							:img_src2="require('@/assets/css-3 logo.svg')"
							:img_src3="require('@/assets/javascript logo.svg')"
							description="This track deals with the aspect of your application that the users interact with. A front-end developer will be able to correctly interpret a given design to the user interface."
						></scope>
					</div>

					<div class="col-lg-4 pb-4">
						<scope
							class="scope-box back-end"
							header="Backend Development"
							:img_src1="require('@/assets/php2 logo.svg')"
							:img_src2="require('@/assets/python-4 logo.svg')"
							:img_src3="require('@/assets/javascript logo.svg')"
							description="This track deals with the aspect of the application the user does not directly interact with. It allows the frontend function either by running some back-end code or connecting to the database."
						></scope>
					</div>

					<div class="col-lg-4 pb-4">
						<scope
							class="scope-box design"
							header="Product Design"
							:img_src1="require('@/assets/adobe-xd logo.svg')"
							:img_src2="require('@/assets/Figma logo.svg')"
							description="This track deals with creating a graphic plan for an application. You will learn to convert project documentation into viewable and understandable graphic design for the developers to work with."
						></scope>
					</div>
				</div>

				<div class="scope-container row m-auto">
					<div class="col-lg-4 pb-4">
						<scope
							class="scope-box dev-ops"
							header="DevOPS"
							:img_src1="require('@/assets/Ubuntu logo.svg')"
							:img_src2="require('@/assets/Bash logo.svg')"
							:img_src3="require('@/assets/aws logo.svg')"
							description="The DevOps track is an extension of the backend track. It involves tools that'll allow the participant to deploy solutions for public use."
						></scope>
					</div>

					<div class="col-lg-4 pb-4">
						<scope
							class="scope-box full-stack"
							header="Fullstack Development"
							:img_src1="require('@/assets/html.svg')"
							:img_src2="require('@/assets/css-3 logo.svg')"
							:img_src3="require('@/assets/javascript logo.svg')"
							:img_src4="require('@/assets/python-4 logo.svg')"
							description="A combination of frontend, backend, and DevOps. This track will only be available to participants who have the time to dedicate to the training."
						></scope>
					</div>

					<div class="col-lg-4 pb-4">
						<scope
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
						><Button
							class="rounded-pill pt-2 pb-2 ps-4 pe-4 m-0"
							value="Enroll Now"
					/></a>
				</div>
			</div>
		</section>

		<section class="section6 m-auto">
			<div>
				<hr class="m-3 md-0" />
			</div>
			<div class="section6-container" id="faq">
				<div class="d-flex justify-content-start mb-0">
					<img
						src="@/assets/section7wire.svg"
						alt=""
						width="20%"
						class="ms-5"
					/>
				</div>

				<div class="faq-head text-center">
					<p class="faq-q m-0">Got Questions?</p>
					<p class="faq-intro fw-semibold">Frequently Asked Questions</p>
				</div>

				<div class="faqs mt-5 pt-5 m-auto">
					<FAQ />
				</div>
			</div>
		</section>

		<div class="got-q text-center pt-5 pb-5">
			<p class="mb-0 pb-2">Still got questions?</p>
			<div class="tweet-btn d-flex justify-content-center">
				<a href="https://twitter.com/thezuriteam" target="blank">
					<Button
						class="rounded-pill ps-2 pe-4 m-0 border-0"
						value="Tweet them at us"
						:imgsrc="require('@/assets/twitter.svg')"
					/>
				</a>
			</div>
		</div>

		<section class="section7">
			<div>
				<hr class="m-3 md-0" />
			</div>
			<div class="section7-heading mt-5">
				<div class="m-0">
					<img src="@/assets/section7wire.svg" alt="" style="width: 20%" />
				</div>

				<div class="d-flex justify-content-end star">
					<img src="@/assets/Star1.svg" alt="" width="12%" />
				</div>

				<div class="text-center structure">
					<p class="heading m-0">Structure</p>
					<p class="sub-head fw-semibold">Program Structure</p>
					<p class="desc">
						There are 2 broad paths in this program based on your availability
					</p>
				</div>
			</div>

			<div class="section7-container">
				<div class="structure-block row pt-2">
					<div class="col-lg-6 p-4">
						<div class="time-structure">
							<p class="head">Full-time</p>
							<p class="sub-head">
								Requires at least 25 hours weekly on program content
							</p>

							<p class="title">Available Tracks:</p>
							<ul>
								<li>
									Full Stack: Backend(Python, JavaScript), Frontend(HTML, CSS,
									JavaScript) & DevOps
								</li>
								<li>Design: Figma, Adobe XD</li>
							</ul>

							<p class="title">Phases:</p>
							<ul>
								<li>Training Phase</li>
								<li>Project Phase</li>
							</ul>

							<p class="title">Post Program:</p>
							<ul>
								<li>Certification of Attendance</li>
								<li>
									<a href="https://internship.zuri.team" style="color: #fff"
										>Zuri Internship
										<img src="@/assets/clarity.svg" alt="" width="15px"
									/></a>
								</li>
								<li>
									Laptop Reward (Upgrade or new one)
									<img src="@/assets/clarity.svg" alt="" width="15px" />
								</li>
								<li>
									Job Placement
									<img src="@/assets/clarity.svg" alt="" width="15px" />
								</li>
								<li>
									Zuri talent Pool
									<img src="@/assets/clarity.svg" alt="" width="15px" />
								</li>
								<li>
									More Training:
									<img src="@/assets/clarity.svg" alt="" width="15px" />
								</li>
								<li class="list-unstyled">Interview Prep</li>
								<li class="list-unstyled">Algorithms & Data Structure</li>
								<li class="list-unstyled">Freelance Setup & Training</li>
								<li class="list-unstyled">LinkedIn Optimization</li>
								<li class="list-unstyled">CV Review</li>
							</ul>
							<img src="@/assets/hour.png" alt="" class="hour-glass" />
						</div>
					</div>

					<div class="col-lg-6 p-4">
						<div class="time-structure">
							<p class="head">Part-time</p>
							<p class="sub-head">
								Requires at least 11 hours weekly on program content.
							</p>

							<p class="title">Available Tracks:</p>
							<ul>
								<li>Frontend:</li>
								<li class="list-unstyled">HTML, CSS, JavaScript</li>
								<li>Backend: Can only select one backend language</li>
								<li class="list-unstyled">Python,</li>
								<li class="list-unstyled">PHP,</li>
								<li class="list-unstyled">JavaScript</li>
								<li>Design:</li>

								<li class="list-unstyled">Figma, Adobe XD</li>
							</ul>

							<p class="title">Phases:</p>
							<ul>
								<li>Training Phase</li>
							</ul>

							<p class="title">Post Program:</p>
							<ul>
								<li>Certification of Attendance</li>
								<li>Zuri Internship</li>
							</ul>
							<img src="@/assets/time.png" alt="" class="time" />
						</div>
					</div>
				</div>
			</div>

			<div>
				<img src="@/assets/circle.png" alt="" class="d-flex circle" />
			</div>

			<div></div>
			<div></div>
			<div></div>
			<div></div>
		</section>

		<section class="section8">
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
		</section>

		<footer>
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

			<div class="pt-4 pb-4">
				<div class="bottom-links pb-4 pt-4">
					<p class="mb-4">
						<a href="https://ingressive.org">Ingressive For Good</a>
					</p>
					<p><a href="https://training.zuri.team/privacy">Privacy Policy</a></p>
				</div>

				<hr />

				<div class="copy">
					<p>&copy; 2022 Zuri Training</p>
				</div>
			</div>
		</footer>
	</div>
</template>

<script>
	import NavBar from "@/components/NavBar.vue";
	import Button from "@/components/Button.vue";
	import WhyUsBox from "@/components/WhyUsBox.vue";
	import Benefits from "@/components/Benefits.vue";
	import Scope from "@/components/Scope.vue";
	import FAQ from "@/components/FAQ.vue";

	export default {
		name: "ZuriTraining",
		components: {
			NavBar,
			Button,
			WhyUsBox,
			Benefits,
			Scope,
			FAQ,
		},
	};
</script>

<style>
	.section1 {
		font-family: Graphik !important;
		max-width: 1440px !important;
		width: 90% !important;
	}
	.lady1 {
		width: 100% !important;
		mix-blend-mode: darken !important;
	}
	.lady1 img {
		width: 100% !important;
		margin: auto;
	}
	.hero-texts .hero-small {
		font-size: 1.1em;
		color: #e7332b;
		line-height: 24% !important;
	}
	.hero-texts .hero-large {
		color: #1b1a20 !important;
		font-size: 1.8em;
		line-height: 32px;
	}
	.line {
		margin: 0 32px 28px -20px;
	}
	.hero-texts .hero-medium {
		font-size: 1.02em;
		color: #1b1a20 !important;
		line-height: 22px;
	}
	.enroll-btn a button {
		font-size: 1.2em;
		background-color: #e7332b !important;
		color: #fff;
		border: none;
		cursor: pointer;
	}
	.wire {
		width: 64% !important;
	}
	.wire img {
		width: 22% !important;
	}

	.guy1 {
		display: none;
	}
	.section2 {
		font-family: Graphik !important;
		max-width: 1440px !important;
		width: 95% !important;
	}
	.section2 hr {
		opacity: 20%;
		border: 0.2px solid #514949;
	}
	.i4g-text {
		font-size: 1.25em;
		line-height: 130%;
	}
	.i4g-img {
		padding: 16px 10px;
	}
	.i4g-img-main {
		margin: auto;
	}
	.i4g-img-main img {
		width: 52% !important;
	}
	.i4g-end-text {
		padding: 16px 10px;
	}
	.i4g-end-text p {
		font-size: 1.1em;
		line-height: 130% !important;
	}
	.i4g-end-text span a {
		color: #43b97f;
		cursor: pointer;
	}
	.why-us-text .why-us-q {
		color: #e7332b;
		font-size: 1.1em;
		line-height: 130%;
	}
	.why-us-intro {
		font-size: 1.59em;
		font-weight: 600;
		line-height: 130%;
	}
	.wire3 img {
		width: 15% !important;
	}
	.star3 {
		display: none;
	}
	.section3 {
		background: linear-gradient(
			180deg,
			rgba(255, 244, 240, 0),
			#fff4f098 17.19%,
			#fff4f0a9 84.37%,
			rgba(255, 244, 240, 0)
		) !important;
		font-family: Graphik !important;
		width: 100% !important;
		margin: auto !important;
	}
	.box-container {
		width: 95% !important;
		max-width: 1440px !important;
	}
	.box1 {
		padding: 54px 52px 63px 40px;
		color: #fff;
		background: #e7332b !important;
		border-radius: 18px !important;
		transition: transform 0.3s ease !important;
		box-shadow: 0px 10px 20px 0 #ffd1c0;
		transition: 0.5s ease;
	}
	.box1:hover {
		transform: translate(0, -10px);
	}
	.box2 {
		padding: 54px 52px 63px 40px;
		color: #000;
		background: #fff !important;
		border-radius: 18px !important;
		transition: transform 0.3s ease !important;
		box-shadow: 0px 10px 20px 0 #ffd9cc;
		transition: 0.5s ease;
	}
	.box2:hover {
		transform: translate(0, -10px);
	}
	.box1 .why-us-img,
	.box2 .why-us-img {
		display: flex;
		float: right !important;
		width: 42%;
		margin-top: -55px;
		margin-right: -53px;
	}
	.box1 .num,
	.box2 .num {
		font-size: 2.7em;
		font-weight: 600;
	}
	.box1 .head,
	.box2 .head {
		font-size: 1.8em;
		font-weight: 500;
		width: 160px;
	}
	.box1 .details,
	.box2 .details {
		font-size: 1.1em;
		padding-top: 3px;
	}
	.section4 {
		font-family: Graphik !important;
		background: #e7332b;
		margin-top: 149px;
		color: #fff;
		width: 100%;
		max-width: 1440px;
		margin: auto;
		overflow-x: hidden !important;
	}
	.wire2 img {
		width: 18% !important;
	}
	.start {
		font-size: 1.1em;
		margin: 0;
	}
	.high {
		font-size: 1.9em;
		font-weight: 600;
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
	.section4 .container {
		width: 100%;
		flex-flow: row wrap;
		margin-top: 28px;
		padding: 0;
	}
	.section4 .benefits {
		flex-basis: 50%;
		padding: 15px 5px 10px 5px;
	}
	.section4-img {
		width: 100%;
		margin-top: 10px;
	}
	.section4-img img {
		width: 100%;
	}
	.section4-dot {
		width: 100%;
	}
	.section4-dot img {
		margin: 35px 20px;
		width: 12%;
	}
	.section5 {
		background: linear-gradient(
			180deg,
			rgba(255, 244, 240, 0),
			#fffaf8d4 17.19%,
			#fff6f3 84.37%,
			rgba(255, 244, 240, 0)
		) !important;
		font-family: Graphik !important;
	}
	.section5-container {
		padding: 70px 20px 0;
		width: 100% !important;
		margin: auto !important;
	}
	.scope .head {
		color: #e7332b;
		font-size: 1.15em;
		line-height: 130%;
		margin: 0;
	}
	.scope .sub-head {
		font-size: 1.55em;
		font-weight: 600;
		line-height: 130%;
	}
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
		font-weight: 600;
	}
	.scope-box img {
		margin-right: 15px;
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
	.section6-container {
		font-family: Graphik !important;
		width: 100%;
		padding: 20px;
		max-width: 1440px !important;
		margin: auto !important;
	}
	.faq-q {
		font-size: 1.1em;
		color: #e7332b;
		line-height: 130%;
	}
	.faq-intro {
		font-size: 1.5em;
	}
	.faqs {
		width: 100% !important;
	}
	.got-q p {
		font-size: 1.1em;
	}
	.tweet-btn a button {
		font-size: 1.16em;
		background-color: #e7332b !important;
		color: #fff;
		cursor: pointer;
	}
	.tweet-btn a img {
		width: 50px;
	}
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
	}
	.section7-container {
		font-family: Graphik !important;
		width: 100%;
		max-width: 1440px;
		margin: auto !important;
		padding: 10px 20px;
	}
	.time-structure {
		background: #1b1a20 !important;
		color: #fff;
		padding: 64px 45px !important;
		border-radius: 65px;
		box-shadow: 0px 20px 50px 30px #ffe2d872 !important;
		box-sizing: border-box !important;
		/* height: 740px !important; */
	}
	.time-structure .head {
		font-size: 2.17em;
		font-weight: 600;
	}
	.time-structure .title {
		font-size: 1.15em;
		font-weight: 600;
		margin: 0;
	}
	.time-structure ul {
		padding-left: 16px;
	}
	.hour-glass {
		width: 25%;
		display: flex;
		float: right;
		margin-top: -90px;
		/* margin-left: -80px; */
	}
	.time {
		width: 45%;
		display: flex;
		float: right;
		margin-top: -120px;
	}
	.circle {
		width: 35%;
		float: right;
		margin-top: -110px;
	}
	.section8-container {
		font-family: Graphik !important;
		width: 90%;
		max-width: 1440px !important;
		background: #e7332b;
		margin-top: 30px !important;
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
		width: 20%;
	}
	.started {
		margin: auto;
		padding: 100px 50px 0;
		width: 100%;
	}
	.started .head {
		font-size: 1.2em;
		/* padding: 0 50px; */
	}
	.started .desc {
		font-size: 1.9em;
		line-height: 130%;
		font-weight: 600;
		padding-bottom: 35px;
	}
	.started .enroll-btn button {
		font-size: 1.2em;
		background-color: #fff !important;
		color: #e7332b;
		border: none;
		cursor: pointer;
	}
	footer {
		font-family: Graphik !important;
		width: 90%;
		max-width: 1440px;
		margin: auto;
		padding-top: 90px;
	}
	.foot-links {
		flex-wrap: wrap;
		justify-content: center;
	}
	.media-links a {
		margin-right: 10px;
	}
	.bottom-links {
		text-align: center;
	}
	.bottom-links p a {
		font-size: 1em;
		text-decoration: none;
		color: #1b1a20;
	}
	.copy {
		text-align: center;
		font-size: 1em;
	}
	@media screen and (min-width: 1200px) {
		.lady1 img {
			display: flex;
			margin: auto;
			width: 76% !important;
		}
		.section1 {
			max-width: 1440px !important;
			width: 90% !important;
		}
	}

	@media screen and (max-width: 800px) {
		.i4g-img-main img {
			width: 42% !important;
		}
	}
</style>