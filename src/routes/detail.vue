<template>
  <div class="topBg">
    <img src="" alt="" class="backBtn">
    <div class="title">2주만에 미적분 A+ 맞자!</div>
    <img src="" alt="" class="teacher">
  </div>
  <div class="detail">
    <div class="navbar"></div>
    <div class="contents">
      <div class="subject">
        <span class="left">과목명</span>
        <span class="right">미분적분학2</span>
      </div>
      <div class="rate">
        <div class="left">후기</div>
        <img src="" alt="" class="starRate">
        <span class="rateCount">(24)</span>
        <div class="thumbnails">
          <div class="good">

          </div>
          <div class="bad">

          </div>
        </div>
      </div>
      <div class="introduce">
        <div class="left">소개</div>
        <div class="right">

        </div>
      </div>
      <div class="price">
        <div class="left">현재 판매가</div>
        <div class="right">35,000원</div>
      </div>
      <div class="detailPage">
        <div class="left">상세 페이지</div>
        <img src="" alt="" class="right">
      </div>
    </div>
  </div>
  <div class="btnContainer">
    <button class="toBuy">도전하기🏆</button>
  </div>
</template>

<style lang="scss" scoped>
  @mixin box {
    border-radius: 17px;
    background-color: #fff;
    box-shadow: 4px 3px 15px;
  }

  .topBg {
    position: relative;
    .backBtn {
      position: absolute;
      top: 36px;
      left: 36px; 
    }
    .title {
      position: absolute;
      left: 36px;
      top: 98px;
    }
    .teacher {
      position: absolute;
      right: 36px;
      top: 98px;
    }
  }
  .detail {
    //y:204
    border-radius: 39px 39px 0px 0px;
    background-color: #F7F7F7;
    width: 100%;
    .navbar {
      border-radius: 3px;
      width: 6px;
      height: 70px;
      position: absolute;
      top: 9px;
      margin: auto;
      left: 0px;
      right: 0px;
    }
    .subject {
      width: 318px;
      position: absolute;
      top: 59px;
      left: 36px;
      .left {
        position: absolute;
        left: 0px;
      }
      .right {
        position: absolute;
        right: 0px;
      }
    }
    .rate {
      width: 318px;
      position: absolute;
      top: 98px;
      left: 36px;
      .left {
        position: absolute;
        left: 0px;
      }
      .starRate {
        position: absolute;
        left: 144px;
      }
      .rateCount {
        position: absolute;
        right: 0px;
      }
      .thumbnails {
        width: 318px;
        height: 128px;
        position: absolute;
        left: 0px;
        top: 36px;
        .good {
          width: 152px;
          height: 128px;
          @include box;
          position: absolute;
          left: 0px;
          top: 0px;
        }
        .bad {
          width: 152px;
          height: 128px;
          @include box;
          position: absolute;
          right: 0px;
          top: 0px;
        }
      }
    }
    .introduce {
      position: absolute;
      top: 273px;
      left: 36px;
      width: 318px;
      height: 206px;
      .left {
        position: absolute;
        left: 0px;
        top: 0px;
      }
      .right {
        position: absolute;
        left: 0px;
        top: 39px;
        @include box;
        width: 318px;
        height: 167px;
      }
    }
    .price {
      width: 318px;
      position: absolute;
      top: 491px;
      left: 36px;
      .left {
        position: absolute;
        left: 0px;
      }
      .right {
        position: absolute;
        right: 0px;
      }
    }
    .detailPage {
      width: 318px;
      position: absolute;
      top: 530px;
      left: 36px;
      .left {
        position: absolute;
        left: 0px;
      }
      .right {
        position: absolute;
        top: 36px;
        right: 0px;
        @include box;
        width: 318px;
        height: 165px;
      }
    }
    .btnContainer {
      display: flex;
      justify-content: center;
      position: fixed;
      bottom: 0px;
      width: 390px;
      height: 103px;
      backdrop-filter: blur(30px);
      .toBuy {
        position: absolute;
        top: 3px;
      }
    }
  }
</style>
