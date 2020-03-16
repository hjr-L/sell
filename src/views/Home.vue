<template>
  <div class="home">
    <home-header />
    <home-list />
  </div>
</template>
<script>
import HomeHeader from "../components/Home/header";
import HomeList from "../components/Home/list.vue";
export default {
  name: "Home",
  components: {
    HomeHeader,
    HomeList
  }
};
</script>
