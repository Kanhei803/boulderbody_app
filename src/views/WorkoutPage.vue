<template>
	<div id="app_style" class="d-flex flex-column justify-content-center mx-auto">
		<div class="sticky_navbar">
			<NavBar />
		</div>
		<div>
			<h1>Workout Page</h1>
		</div>
		<h2>Push-Ups</h2>
		<span>Inclined Pushup x10</span>
		<span>Declined Pushup x10</span>
		<span>Pushup x10</span>
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

span {
	font-family: Arial, Helvetica, sans-serif;
	font-size: x-large;
	font-weight: bold;
	color: white;
	text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.5);
}
</style>
