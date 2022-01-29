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
  width: 90%;
  text-align: center;
  height: 500px;
  border: 3px solid black;
  margin: 0 auto;
  height: 800px;
  margin-top: 150px;
}
</style>
