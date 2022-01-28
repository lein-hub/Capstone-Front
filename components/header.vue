<template>
  <div id="headermainbox">
    <img src="@/assets/Logo.png" class="logoimg">

    <ul id="headerulbox">
      <div class="ulbox">
        <p class="headerlitilte">게임 가이드</p>
        <p class="headerlitilte">랭킹</p>
        <p class="headerlitilte">커뮤니티</p>
        <p class="headerlitilte">고객지원</p>
      </div>

      <div class="libox">
          <ul class="tilteulbox">
          <li>게임 설명</li>
          <li>직업 소개</li>
          <li>튜토리얼 가이드</li>
          </ul>

        <ul class="tilteulbox">
          <li>레벨 랭킹</li>
          <li>신뢰도 랭킹</li>
        </ul>

        <ul class="tilteulbox">
          <li>공지 사항</li>
          <li>전체 게시판</li>
          <li>자유 게시판</li>
          <li>정보 게시판</li>
          <li>인기 게시판</li>
        </ul>

        <ul class="tilteulbox">
          <li>문의 하기</li>
          <li>신고 하기</li>
        </ul>
      </div>


    </ul>

  </div>
</template>

<script>
export default {
  name: 'CapstoneHeader',

  data() {
    return {

    };
  },

  methods: {

  },
};
</script>

<style lang="scss" scoped>
@import '~assets/header.scss'
</style>
