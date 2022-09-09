<template>
	<program-structure-intro></program-structure-intro>

	<div class="section7-container">
		<div class="structure-block row pt-2">
			<div class="move">
				<img src="@/assets/move.svg" alt="" />
			</div>

			<program-structure></program-structure>
		</div>
	</div>
</template>

<script>
	import ProgramStructureIntro from "@/components/ProgramStructureIntro.vue";
	import ProgramStructure from "@/components/ProgramStructure.vue";
	export default {
		name: "Structure-section",
		components: {
			ProgramStructureIntro,
			ProgramStructure,
		},
	};
</script>

<style>
	.section7-container {
		font-family: "Graphik" !important;
		width: 95%;
		max-width: 1440px;
		margin: auto !important;
		padding: 10px 20px;
	}
</style>