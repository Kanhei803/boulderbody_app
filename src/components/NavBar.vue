<template>
  <div id="app">
    <div class="d-flex justify-content-around mx-auto">
      <div class="d-flex flex-column">
        <router-link to="/" class="navbar_link"><img class="logo d-flex" src="../assets/images/Boulderbody_Logo.png"
            alt="Boulderbody Logo"></router-link>
        <h2><router-link to="/" class="navbar_link">BoulderBody</router-link></h2>
      </div>
      <div class="d-flex align-items-end">
        <h2><router-link to="/about" class="navbar_link mx-2">About</router-link></h2>
        <h2><router-link to="/workout" class="navbar_link mx-2">Workout</router-link></h2>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'NavBar',
  components: {
  },
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
#app {
  max-width: 1200px;
}

.logo {
  max-width: 125px;
  max-height: 125px;
}

.navbar_link {
  text-decoration: none;
  color: inherit;
}
</style>