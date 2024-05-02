<template>
  <div>
    <div><navigation-bar></navigation-bar></div>
    <div><details-page></details-page></div>
    <div><the-footer></the-footer></div>
  </div>
</template>

<script>
import NavigationBar from "./components/NavigationBar.vue";
import DetailsPage from "./components/DetailsPage.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  components: { NavigationBar, DetailsPage, TheFooter },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inter&display=swap");
</style>