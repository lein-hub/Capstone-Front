<template>
  <div class="profilebox">

    <div class="profile1">
      <img src="@/assets/test.jpg" class="profileimg">
    </div>

    <div class="profile2">
      <button>로그아웃</button>
      <p>Lv.30 Mirai님</p>
      <p>덤벼라마!</p>
    </div>

    <div class="profile3">
      <button class="profilebutton" v-on:click="friend">친구</button>
      <button class="profilebutton"  v-on:click="ball">알림</button>
      <button class="profilebutton">
        <NuxtLink to="/" class="linkpage">My페이지</NuxtLink>
      </button>
    </div>

    <div class="profile4" v-if="show1">
      <p>친구</p>
    </div>

    <div class="profile5" v-if="show2">
      <p>알림</p>
    </div>

  </div>
</template>

<script>
export default {
  name: 'CapstoneProfile',

  data() {
    return {
      show1: false,
      show2: false
    };
  },

  methods: {
    friend(){
      this.show1 = !this.show1;
      if(this.show2 == true){
      this.show2 = !this.show2;
      }
    },
    ball(){
      this.show2 = !this.show2;
      if(this.show1 == true){
      this.show1 = !this.show1;
      }
    }
  },
};
</script>

<style lang="scss" scoped>
@import '~assets/profile.scss'
</style>
