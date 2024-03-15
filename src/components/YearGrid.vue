<template>
	<div class="col">
		<div class="row bordeado">
			<YearColumn msg="Primer" />
			<YearColumn msg="Segundo" clase="border-center" />
			<YearColumn msg="Tercer" />
		</div>

		<div class="row bordeado">
			<YearColumn msg="Cuarto" />
			<YearColumn msg="Quinto" clase="border-center" />
			<YearColumn msg="Sexto" />
		</div>
	</div>
</template>

<script>
import YearColumn from "./YearColumn.vue";

export default {
	name: "YearGrid",
	components: { YearColumn },
};
</script>

<style scoped>
.bordeado {
	border-top: 1px solid black;
}
</style>
