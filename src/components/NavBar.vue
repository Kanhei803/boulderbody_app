<template>
  <div id="app">
    <div class="d-flex justify-content-between align-items-center">
      <div class="d-flex flex-column">
        <router-link to="/" class="navbar_link"><img class="logo d-flex" src="../assets/images/Boulderbody_Logo.png"
            alt="Boulderbody Logo"></router-link>
      </div>
      <div class="d-flex mx-3">
        <span><router-link to="/workout" class="navbar_link mx-5">Workout</router-link></span>
        <span><router-link to="/about" class="navbar_link mx-5">About</router-link></span>
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
  display: flex;
  flex-direction: column;
  height: 100%;
}

.logo {
  max-width: 125px;
  max-height: 125px;
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