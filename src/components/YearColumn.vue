<template>
	<div class="col-lg-4 cardYear" :class="clase">
		<h3 class="text-left">{{ msg }} año</h3>
	</div>
</template>

<script>
export default {
	name: "YearColumn",
	props: { msg: String, clase: String },
};
</script>

<style scoped>
.cardYear {
	height: 33vh;
	justify-content: stretch;
	display: flex;
	align-items: center;
	text-align: left;
}

.border-center {
	border-left: 1px solid black;
	border-right: 1px solid black;
}
</style>
