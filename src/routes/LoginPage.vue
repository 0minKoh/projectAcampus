<template>
<div class="bg">
  <img src="" alt="" class="logo">
  <div class="loginGroup">
    <div class="title">빛의 속도로, 로그인</div>
    <div class="kakao">
      <img src="" alt="" class="kakaoLogo">
      <div class="main">카카오톡으로 로그인</div>
    </div>
    <div class="naver">
      <img src="" alt="" class="naverLogo">
      <div class="main">네이버로 로그인</div>
    </div>
    <div class="email">
      <img src="" alt="" class="emailLogo">
      <div class="main">이메일로 로그인</div>
    </div>
  </div>
  <div class="signinGroup">
    <div class="title">아직 회원이 아니신가요?</div>
    <div class="btn">20초 만에 회원가입하기</div>
  </div>
</div>
</template>

<style lang="scss" scoped>
 @mixin title {
    font-weight: 700;
    font-size: 20px;
  }

  @mixin general {
    font-weight: 400;
    font-size: 10px;
  }

  .bg {
    background-color: #F7F7F7;
  }

  img.logo {
    position: relative;
    left: 36px;
    top: 36px;
  }
  .loginGroup {
    position: absolute;
    top: 139px;
    left: 36px;
    .title {
      position: absolute;
      left: 0px;
      top: 0px;
      @include title;
    }
    .kakao {
      position: absolute;
      top: 61px;
      left: 0px;
      width: 138px;
      height: 57px;
      background-color: #FFE502;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .naver {
      position: absolute;
      top: 137px;
      left: 0px;
      width: 138px;
      height: 57px;
      background-color: #00C73C;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .email {
      position: absolute;
      top: 210px;
      left: 0px;
      width: 138px;
      height: 57px;
      background-color: #707070;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }
  .signinGroup {
    position: absolute;
    top: 515px;
    left: 0px;
    right: 0px;
    margin: auto;
    width: 318px;
    height: 612px;
    display: flex;
    justify-content: center;
    .title {
      @include general;
      font-size: 25px;
      position: absolute;
      top: 0px;
      text-align: center;
    }
    .btn {
      position: absolute;
      bottom: 0px;
      background-color: #AF13CE;
      border-radius: 35px;
      width: 246px;
      height: 46px;
    }
  }
</style>