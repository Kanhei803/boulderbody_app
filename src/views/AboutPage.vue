<template>
	<div id="app_style" class="d-flex flex-column justify-content-center mx-auto">
		<div class="sticky_navbar">
			<NavBar />
		</div>
		<div>
			<h1>About Page</h1>
		</div>
    <h2>Our Team:</h2>
    <p>Kenjy</p>
    <p>Phil</p>
	</div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
	name: "HomePage",
	components: {
		NavBar,
	},
	data() {
		return {};
	},
	methods: {},
};
</script>

<style scoped>
#app_style {
	max-width: 1300px;
}
.sticky_navbar {
	position: sticky;
	top: 0;
	background-color: rgb(255, 156, 85);
	z-index: 100;
}
</style>
