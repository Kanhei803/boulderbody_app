<template>
	<nav id="navbar_style">
		<div class="d-flex justify-content-between align-items-center">
			<div class="d-flex flex-column">
				<router-link to="/" class="navbar_link"><img class="logo d-flex" src="../assets/images/Boulderbody_Logo.png" alt="Boulderbody Logo" /></router-link>
				<span><router-link to="/" class="navbar_link mx-5">BoulderBody</router-link></span>
			</div>
			<div class="d-flex mx-3">
				<span><router-link to="/workout" class="navbar_link mx-5">Workout</router-link></span>
				<span><router-link to="/about" class="navbar_link mx-5">About</router-link></span>
			</div>
		</div>
	</nav>
</template>

<script>
export default {
	name: "NavBar",
	components: {},
	data() {
		return {
			// Your data properties here
		};
	},
	methods: {
		// Your methods here
	},
};
</script>

<style>
#navbar_style {
	max-width: 1300px;
}

.logo {
	max-width: 150px;
	max-height: 150px;
}

.navbar_link {
	text-decoration: none;
	color: inherit;
}

span {
	font-family: Arial, Helvetica, sans-serif;
	font-size: x-large;
	font-weight: bold;
	color: white;
	text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.5);
}
</style>
