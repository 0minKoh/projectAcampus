<template>
<div class="container">
  <div class="loginContainer">
    <img src="" alt="" class="profile">
    <div class="login">로그인 하기</div>
    <img src="" alt="" class="nextBtn">
  </div>
  <div class="signin">
    <span>아직 회원이 아니신가요?</span>
    <button class="btn">20초만에 회원가입하기</button>
  </div>
  <div class="benefits">
    <span>회원가입하면<br/>이런 걸 얻을 수 있어요</span>
    <div class="cards">
      <div class="card1">
        <img src="" alt="">
        <div class="title">무제한 과제/자료</div>
        <div class="sub">A+선배의 과제 우수사례 다운로드</div>
      </div>
      <div class="card2">
        <img src="" alt="">
        <div class="title">맞춤형 스터디</div>
        <div class="sub">OO 대학교, OOO교수님, OO개론</div>
      </div>
      <div class="card3">
        <img src="" alt="">
        <div class="title">A+을 위한 지름길</div>
        <div class="sub">가장 빠르게 점수 올리는 공부</div>
      </div>
    </div>
  </div>
</div>
  
</template>

<style lang="scss" scoped>
  @mixin box {
    border-radius: 17px;
    background-color: #fff;
    box-shadow: 4px 3px 15px;
  }

  @mixin title {
  font-weight: 700;
  font-size: 20px;
  }

  @mixin general {
    font-weight: 400;
    font-size: 10px;
  }
.container {
  background-color: #F7F7F7;
}

  .loginContainer {
    width: 390px;
    height: 99px;
    position: relative;
    border-radius: 0px 0px 36px 36px;
    background-color: #EEEEEE;
    .profile {
      position: absolute;
      top: 36px;
      left: 36px;
    }
    .login {
      position: absolute;
      top: 36px;
      left: 97px;
    }
    .nextBtn {
      position: absolute;
      top: 36px;
      left: 202px;
    }
  }
  .signin {
    position: absolute;
    width: 100%;
    height: 98px;
    top: 131px;
    left: 83px;
    display: flex;
    justify-content: center;
    span { 
      position: absolute;
      top: 0px;
      @include title;
    }
    .btn {
      position: absolute;
      bottom: 0px;
      background-color: #AF13CE;
      border-radius: 35px;
      width: 263px;
      height: 57px;
    }
  }
  .benefits {
    position: absolute;
    top: 281px;
    left: 36px;
    width: 318px;
    height: auto;
    span {
      position: absolute;
      top: 0px;
      left: 0px;
      @include title;
      margin-bottom: 30px;
    }
    .cards {
      position: relative;
      width: 318px;
      height: 298px;
      .card1 {
        position: relative;
        width: 100%;
        height: 86px;
        margin-bottom: 20px;
        @include box;
      }
      .card2 {
        position: relative;
        width: 100%;
        height: 86px;
        margin-bottom: 20px;
        @include box;
      }
      .card3 {
        position: relative;
        width: 100%;
        height: 86px;
        margin-bottom: 20px;
        @include box;
      }
    }
  }
</style>

<script>
  //부트스트랩 연동하기
  //grid 사용하기
</script>