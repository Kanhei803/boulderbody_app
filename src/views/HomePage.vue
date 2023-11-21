<template>
  <div id="app">
    <div id="wrapper">
      <div id="app_style" class="mx-auto m-2">
        <NavBar />
      </div>
    </div>
    <div id="app_style" class="mx-auto">
      <h1>Home Page</h1>
    </div>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';

export default {
  name: 'HomePage',
  components: {
    NavBar,
  },
  data() {
    return {

    };
  },
  methods: {

  },
};
</script>

<style>
#wrapper {
  flex: 1;
  background-color: rgb(255, 156, 85)
}

#app_style {
  max-width: 1300px;
}
</style>