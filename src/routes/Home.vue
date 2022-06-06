<template>
  <div class="container">
    <div class="header">
      <div class="intro">
        <h1>HI, Users 🐳</h1>
        <img src="" alt="profile" class="profile">
      </div>
      <div class="navbar">
        <img src="" alt="logo">
        <div class="search">
          <span class="placeholder">search</span>
          <img src="../assets/searchIcon.svg" alt="searchIcon">
        </div>
      </div>
      <div class="banner">
        <img src="" alt="banner">
      </div>
    </div>
    <div class="content">
      <div class="category">
        <div class="top">
          <span>미분적분학</span>
          <button>more</button>
        </div>
        <div class="classCards">
          <div class="classCard">
            <div class="cardContainer">
              <div class="bg">
                <img class="bgImg" src="" alt="bgImg">
                <div class="teacher">
                  <img src="" alt="profile">
                  <span class="name">고영민</span>
                </div>
                <div class="price">30,000</div>
              </div>
              <span class="title">미분적분학</span>
              <span class="date">start at 5/30 2022</span>
              <div class="detail">Lorem Ipsum</div>
            </div>
          </div>
        </div>
      </div>
      <div class="category">
        <span>창의적 컴퓨팅</span>
        <button>more</button>
        <div class="classCards">
          <div class="classCard">
            <div class="cardContainer">
              <div class="bg">
                <img class="bgImg" src="" alt="bgImg">
                <div class="teacher">
                  <img src="" alt="profile">
                  <span class="name">고영민</span>
                </div>
                <div class="price">30,000</div>
              </div>
              <span class="title">창의적 컴퓨팅</span>
              <span class="date">start at 5/30 2022</span>
              <div class="detail">Lorem Ipsum</div>
            </div>
          </div>
        </div>
      </div>
      <div class="category">
        <span>공과대학</span>
        <button>more</button>
        <div class="classCards">
          <div class="classCard">
            <div class="cardContainer">
              <div class="bg">
                <img class="bgImg" src="" alt="bgImg">
                <div class="teacher">
                  <img src="" alt="profile">
                  <span class="name">고영민</span>
                </div>
                <div class="price">30,000</div>
              </div>
              <span class="title">공과대학</span>
              <span class="date">start at 5/30 2022</span>
              <div class="detail">Lorem Ipsum</div>
            </div>
          </div>
        </div>
      </div>
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

.intro {
  position: relative;
  display: flex;
  align-items: center;
  h1 {
    font-size: 13px;
  }
  .profile {
    position: absolute;
    right: 0;
  }
}
.navbar {
  position: relative;
  display: flex;
  align-items: center;
  height: fit-content;
  .search {
    display: flex;
    align-items: center;
    position: absolute;
    width: 70%;
    height: 35px;
    border-radius: 18px;
    right: 0;
    background-color: #000;
    span {
      position: absolute;
      left: 14px;
      font-size: 12px;
      color: white;
    }
    img {
      position: absolute;
      right: 14px;
    }
  }
}
.banner {
  position: relative;
  width: 100%;
  height: 131px;
  background-color: #707070;
  border-radius: 19px;
}

.content {
  margin-top: 22px;
  .top {
    display: flex;
    span {
    @include title;
    left: 0px;
    }
    button {
      right: 0px;
      width: 65px;
      height: 24px;
    }
  }
  .cardContainer {
    position: relative;
    width: 154px;
    height: 153px;
    border-radius: 17px;
    .bg {
      display: flex;
      position: absolute;
      left: 0px;
      top: 0px;
      margin: 6px 6px;
      width: 140px;
      height: 85px;
      .teacher {
        display: flex;
        margin: 6px 6px;
        position: absolute;
        bottom: 0px;
        left: 0px;
        width: 52px;
        height: 20px;
        border-radius: 13px;
        .bgImg {
          margin: 3px 3px;
          position: absolute;
          bottom: 0px;
          left: 0px;
        }
        .name {
          margin: 3px 3px;
          position: absolute;
          bottom: 0px;
          right: 0px;
        }
      }
      .price {
        font-size: 7px;
        padding: 5px 2px;
      }
    }
    .title {
      position: relative;
      margin: 6px 6px;
      @include general
    }
    .date {
      position: relative;
      @include general;
      font-size: 6px;
      color: #AF13CE;
    }
    .detail {
      position: relative;
      @include general;
      font-size: 6px;
      margin: 6px 6px;
    }
  }
}
</style>

<script>
export default {
  computed: {
  }
}
</script>
