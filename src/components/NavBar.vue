<template>
  <div>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/workout">Workout</router-link>
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

<style scoped>
/* Your component-specific styles here */
</style>