<template>
	<div class="container-fluid">
		<HeaderName />
		<SubheaderDescription />
		<YearGrid />
	</div>
</template>

<script>
import HeaderName from "./components/HeaderName.vue";
import SubheaderDescription from "./components/SubheaderDescription.vue";
import YearGrid from "./components/YearGrid.vue";

export default {
	name: "App",
	components: { HeaderName, YearGrid, SubheaderDescription },
};
</script>

<style>
#app {
	font-family: "Archivo", sans-serif;
	font-optical-sizing: auto;
	font-style: normal;
	font-weight: 400;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	max-height: 100vh;
}
</style>
