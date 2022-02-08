<template lang="">
  <div class="lobbyBox">
    <profile></profile>
  </div>
</template>
<script>
import profile from "@/components/profile.vue";

export default {
  components: {
    profile,
  },
};
</script>
<style lang="scss">
@import "~assets/lobby.scss";
</style>
