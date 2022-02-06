<template>
    <div class="testbox">
      <profile/>
    </div>
</template>

<script>
import profile from '../components/profile.vue';
export default {
  components: { profile },
  name: 'CapstoneIndex',

  data() {
    return {

    };
  },

  mounted() {

  },

  methods: {

  },
};
</script>

<style lang="scss" scoped>
.testbox{
  width: 100%;
  text-align: center;
  height: 100%;
  border: 3px solid black;
  margin-top: 100px;
}
</style>
