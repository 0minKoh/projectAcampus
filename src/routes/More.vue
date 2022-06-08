<template>
  <div class="bg">
    <div class="nav">
      <img src="" alt="" class="backBtn">
      <div class="title">미분적분학</div>
    </div>
    <div class="hotContainer">
      <div class="title">🔥 가장 Hot한 상품</div>
      <div class="card"></div>
    </div>
    <div class="generalContainer">
      <div class="title">이런거 어떠세요?</div>
      <div class="card"></div>
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



  .bg {
    background-color: #F7F7F7;
    width: 100%;
    height: auto;
    position: relative;
    .nav {
      position: absolute;
      top: 36px;
      left: 36px;
      .backBtn {
        position: absolute;
        left: 0px;
      }
      .title {
        position: absolute;
        left: 20px;
        @include title;
      }
    }
    .hotContainer {
      background-color: #fff;
      width: 318px;
      height: 254px;
      position: absolute;
      left: 36px;
      top: 121px;
      .title {
        position: absolute;
        left: 0px;
        @include title;
      }
      .card {
        //home에서 가져오기
        background-color: #fff;
      }
    }
    .generalContainer {
      background-color: #fff;
      width: 318px;
      height: 254px;
      position: absolute;
      left: 36px;
      top: 383px;
      .title {
        position: absolute;
        left: 0px;
        @include title;
      }
      .card {
        //home에서 가져오기
        background-color: #fff;
      }
    }
  }
</style>