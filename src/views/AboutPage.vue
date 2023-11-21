<template>
  <div>
    <div>
      <NavBar />
    </div>
    <!-- Your Vue template code here -->
    <h1>About Page</h1>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';

export default {
  name: 'AboutPage',
  components: {
    NavBar,
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