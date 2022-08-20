<template>
	<div class="border border-secondary f-a-q" style="--bs-border-opacity: 0.5">
		<div class="qst">
			<a
				class="collapsed d-flex align-items-center justify-content-between"
				data-bs-toggle="collapse"
				href="#faq1"
				:class="[isActive1 ? 'rotate1' : '']"
				@click="toggleClass1"
			>
				<p class="pt-4 pb-2 ps-3 pe-3">
					Would I have to pay to enroll for the training?
				</p>
				<Button
					value="+"
					style="background: transparent"
					class="border-0 p-4 d-flex align-items-center"
				/>
			</a>
		</div>

		<div class="collapse" style="" id="faq1">
			<div class="card-body p-3 fs-6 m-0">
				No, the program is completely free thanks to Ingressive For Good.
			</div>
		</div>
	</div>

	<div class="border border-secondary f-a-q" style="--bs-border-opacity: 0.5">
		<div class="qst">
			<a
				class="collapsed d-flex align-items-center justify-content-between"
				data-bs-toggle="collapse"
				href="#faq2"
				:class="[isActive2 ? 'rotate2' : '']"
				@click="toggleClass2"
			>
				<p class="pt-4 pb-2 ps-3 pe-3">
					What are the things I need to participate?
				</p>
				<Button
					value="+"
					style="background: transparent"
					class="border-0 p-4 d-flex align-items-center"
				/>
			</a>
		</div>

		<div class="collapse" style="" id="faq2">
			<div class="card-body p-3 fs-6 m-0">
				You'll need a laptop, internet connection and the willingness to learn
				through collaboration and mentorship.
			</div>
		</div>
	</div>

	<div class="border border-secondary f-a-q" style="--bs-border-opacity: 0.5">
		<div class="qst">
			<a
				class="collapsed d-flex align-items-center justify-content-between"
				data-bs-toggle="collapse"
				href="#faq3"
				:class="[isActive3 ? 'rotate3' : '']"
				@click="toggleClass3"
			>
				<p class="pt-4 pb-2 ps-3 pe-3">
					What happens if I join and I'm not active?
				</p>
				<Button
					value="+"
					style="background: transparent"
					class="border-0 p-4 d-flex align-items-center"
				/>
			</a>
		</div>

		<div class="collapse" style="" id="faq3">
			<div class="card-body p-3 fs-6 m-0">
				Participants who join the program and stop engaging will be given the
				chance to catch up. You'll also be assigned a 'study-mate' and mentor to
				help you. However, there is the possibility of not being promoted to the
				next stage if you remain inactive for too long.
			</div>
		</div>
	</div>

	<div class="border border-secondary f-a-q" style="--bs-border-opacity: 0.5">
		<div class="qst">
			<a
				class="collapsed d-flex align-items-center justify-content-between"
				data-bs-toggle="collapse"
				href="#faq4"
				:class="[isActive4 ? 'rotate4' : '']"
				@click="toggleClass4"
			>
				<p class="pt-4 pb-2 ps-3 pe-4">
					Can I switch from the part-time track to full-time and vice versa?
				</p>
				<Button
					value="+"
					style="background: transparent"
					class="border-0 p-4 d-flex align-items-center"
				/>
			</a>
		</div>

		<div class="collapse" style="" id="faq4">
			<div class="card-body p-3 fs-6 m-0">
				Unfortunately, no, you cannot switch from part-time to full-time and
				vice-versa.
			</div>
		</div>
	</div>

	<div class="border border-secondary f-a-q" style="--bs-border-opacity: 0.5">
		<div class="qst">
			<a
				class="collapsed d-flex align-items-center justify-content-between"
				data-bs-toggle="collapse"
				href="#faq5"
				:class="[isActive5 ? 'rotate5' : '']"
				@click="toggleClass5"
			>
				<p class="pt-4 pb-2 ps-3 pe-3">Will I get paid?</p>
				<Button
					value="+"
					style="background: transparent"
					class="border-0 p-4 d-flex align-items-center"
				/>
			</a>
		</div>

		<div class="collapse" style="" id="faq5">
			<div class="card-body p-3 fs-6 m-0">
				We reward some participants who complete tasks early, however, this is
				not a weekly reward. All the work that will be done during the program
				are hypothetical.
			</div>
		</div>
	</div>
</template>

<script>
	import Button from "@/components/Button.vue";
	export default {
		name: "F-A-Qs",
		components: {
			Button,
		},
		data() {
			return {
				isActive1: false,
				isActive2: false,
				isActive3: false,
				isActive4: false,
				isActive5: false,
			};
		},
		methods: {
			toggleClass1() {
				this.isActive1 = !this.isActive1;
			},
			toggleClass2() {
				this.isActive2 = !this.isActive2;
			},
			toggleClass3() {
				this.isActive3 = !this.isActive3;
			},
			toggleClass4() {
				this.isActive4 = !this.isActive4;
			},
			toggleClass5() {
				this.isActive5 = !this.isActive5;
			},
		},
	};
</script>

<style>
	.qst a {
		text-decoration: none;
		color: #333;
	}
	.qst a:hover {
		color: #000;
	}
	.qst a p {
		font-size: 1em;
		line-height: 130%;
		font-weight: 500;
	}
	.qst a button {
		font-size: 2em;
		transition: 0.4s;
	}
	.rotate1 button {
		transform: rotate(180deg);
	}
	.rotate2 button {
		transform: rotate(180deg);
	}
	.rotate3 button {
		transform: rotate(180deg);
	}
	.rotate4 button {
		transform: rotate(180deg);
	}
	.rotate5 button {
		transform: rotate(180deg);
	}
</style>