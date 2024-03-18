<template>
  <div>
    <hr />
    <hero />
    <hr />
    <home-content />
  </div>
</template>

<script lang="ts">
import Hero from "../components/Hero.vue";
import HomeContent from "../components/HomeContent.vue";
import Profile from "./Profile.vue";

export default {
  name: "home-view",
  components: {
    Hero,
    HomeContent,
    Profile,
  },
};
</script>

<style lang="css" scoped>
.next-steps .fa-link {
    margin-right: 5px;
}
</style>
