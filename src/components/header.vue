<template>
  <div class="header">
    <nav class="navbar">
      <div class="header_icon">
        <div class="header_img_top"></div>
        <div class="header_img_bottom"></div>
      </div>

      <div class="header_burger">
        <svg
          class="ham hamRotate ham1"
          viewBox="0 0 100 100"
          width="80"
          onclick="this.classList.toggle('active')"
        >
          <path
            class="line top"
            d="m 30,33 h 40 c 0,0 9.044436,-0.654587 9.044436,-8.508902 0,-7.854315 -8.024349,-11.958003 -14.89975,-10.85914 -6.875401,1.098863 -13.637059,4.171617 -13.637059,16.368042 v 40"
          />
          <path class="line middle" d="m 30,50 h 40" />
          <path
            class="line bottom"
            d="m 30,67 h 40 c 12.796276,0 15.357889,-11.717785 15.357889,-26.851538 0,-15.133752 -4.786586,-27.274118 -16.667516,-27.274118 -11.88093,0 -18.499247,6.994427 -18.435284,17.125656 l 0.252538,40"
          />
        </svg>
      </div>
    </nav>

    <div class="header_content">
      <h1 class="header_text">РЕАЛИЗУЕМ КРУПНЕЙШИЕ ПРОЕКТЫ В РОССИИ</h1>
    </div>

    <div class="header_item">
      <p class="header_text_middle">стадионы, газопроводы, мосты, дамбы</p>
    </div>

    <div class="header_footer">
      <ul class="container">
        <li class="header_figure">26</li>
        <li class="header_figure">26</li>
        <li class="header_figure">26</li>
        <li class="header_figure">26</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "header",
};
</script>

<style lang="scss" scoped>
.header {
  background: url("../assets/block_header/Rectangle.png");
  background-size: cover;
  width: 100%;
  height: 740px;
}

.navbar {
  overflow: hidden;
  display: flex;
  width: 100%;
  height: 100px;
}
.header_icon {
  width: 100%;
  display: flex;
  flex-direction: column;
  height: 7rem;
  align-items: center;
}

.header_burger {
  display: flex;
  justify-content: center;
  padding-left: 11rem;
  padding-top: 2rem;
}

.header_content {
  display: flex;
  width: 100%;
  height: 18rem;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.header_text {
  overflow: hidden;
  margin-top: 3rem;

  width: 741px;
  height: 171px;
  display: flex;
  justify-content: center;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 64px;
  line-height: 95px;
  text-align: center;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  color: #fff;
}

.header_item {
  display: flex;
  font-family: "Oswald";
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 27px;
  text-align: center;
  text-transform: uppercase;

  /* White */

  color: #ffffff;
}

.header_text_middle {
  display: flex;
  justify-content: center;
}

.header_footer {
  display: flex;
  justify-content: center;
  margin-top: 199px;
}

.container {
  width: 1100px;
  display: flex;
  justify-content: center;
  background: #f7f7f7;
}

.header_figure {
  display: flex;
  margin-top: 1.2rem;
  justify-content: center;

  width: 13rem;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 72px;
  line-height: 107px;
  text-align: center;
  text-transform: uppercase;
  color: #f7654a;
}
.header_img_top {
  width: 41px;
  height: 41px;
  display: flex;
  background: url("../assets/block_header/Vector (1).png");
  background-size: cover;
  margin-top: 1rem;
}

.header_img_bottom {
  width: 41px;
  height: 41px;
  display: flex;
  background: url("../assets/block_header/Vector.png");
  background-size: cover;
  transform: translateX(-18px) translateY(-21px);
}
body {
  align-items: center;
  display: flex;
  height: 50px;
  justify-content: center;
  margin: 0;
  overflow: hidden;
  position: absolute;
  width: 50px;
}
.ham {
  width: 50px;
  height: 50px;
  background: #f7654a;
  cursor: pointer;
  -webkit-tap-highlight-color: transparent;
  transition: transform 400ms;
  -moz-user-select: none;
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.hamRotate.active {
  transform: rotate(45deg);
}
.hamRotate180.active {
  transform: rotate(180deg);
}
.line {
  fill: none;
  transition: stroke-dasharray 400ms, stroke-dashoffset 400ms;
  stroke: #fff;
  stroke-width: 5.5;
  stroke-linecap: round;
  background: #f7654a;
}
.ham1 .top {
  stroke-dasharray: 40 139;
}
.ham1 .bottom {
  stroke-dasharray: 40 180;
}
.ham1.active .top {
  stroke-dashoffset: -98px;
}
.ham1.active .bottom {
  stroke-dashoffset: -138px;
}
.ham2 .top {
  stroke-dasharray: 40 121;
}
.ham2 .bottom {
  stroke-dasharray: 40 121;
}
.ham2.active .top {
  stroke-dashoffset: -102px;
}
.ham2.active .bottom {
  stroke-dashoffset: -102px;
}
.ham3 .top {
  stroke-dasharray: 40 130;
}
.ham3 .middle {
  stroke-dasharray: 40 140;
}
.ham3 .bottom {
  stroke-dasharray: 40 205;
}
.ham3.active .top {
  stroke-dasharray: 75 130;
  stroke-dashoffset: -63px;
}
.ham3.active .middle {
  stroke-dashoffset: -102px;
}
.ham3.active .bottom {
  stroke-dasharray: 110 205;
  stroke-dashoffset: -86px;
}
.ham4 .top {
  stroke-dasharray: 40 121;
}
.ham4 .bottom {
  stroke-dasharray: 40 121;
}
.ham4.active .top {
  stroke-dashoffset: -68px;
}
.ham4.active .bottom {
  stroke-dashoffset: -68px;
}
.ham5 .top {
  stroke-dasharray: 40 82;
}
.ham5 .bottom {
  stroke-dasharray: 40 82;
}
.ham5.active .top {
  stroke-dasharray: 14 82;
  stroke-dashoffset: -72px;
}
.ham5.active .bottom {
  stroke-dasharray: 14 82;
  stroke-dashoffset: -72px;
}
.ham6 .top {
  stroke-dasharray: 40 172;
}
.ham6 .middle {
  stroke-dasharray: 40 111;
}
.ham6 .bottom {
  stroke-dasharray: 40 172;
}
.ham6.active .top {
  stroke-dashoffset: -132px;
}
.ham6.active .middle {
  stroke-dashoffset: -71px;
}
.ham6.active .bottom {
  stroke-dashoffset: -132px;
}
.ham7 .top {
  stroke-dasharray: 40 82;
}
.ham7 .middle {
  stroke-dasharray: 40 111;
}
.ham7 .bottom {
  stroke-dasharray: 40 161;
}
.ham7.active .top {
  stroke-dasharray: 17 82;
  stroke-dashoffset: -62px;
}
.ham7.active .middle {
  stroke-dashoffset: 23px;
}
.ham7.active .bottom {
  stroke-dashoffset: -83px;
}
.ham8 .top {
  stroke-dasharray: 40 160;
}
.ham8 .middle {
  stroke-dasharray: 40 142;
  transform-origin: 50%;
  transition: transform 400ms;
}
.ham8 .bottom {
  stroke-dasharray: 40 85;
  transform-origin: 50%;
  transition: transform 400ms, stroke-dashoffset 400ms;
}
.ham8.active .top {
  stroke-dashoffset: -64px;
}
.ham8.active .middle {
  //stroke-dashoffset: -20px;
  transform: rotate(90deg);
}
.ham8.active .bottom {
  stroke-dashoffset: -64px;
}
</style>
