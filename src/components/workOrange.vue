<template>
  <div class="orange">
    <div class="orange_block_one">
      <div class="container">
        <h1 class="orange_text_top">ХОТИТЕ С НАМИ РАБОТАТЬ?</h1>
        <h1 class="orange_text_bottom">
          ОСТАВЬТЕ ЗАЯВКУ И МЫ СВЯЖЕМСЯ С ВАМИ!
        </h1>
      </div>
    </div>

    <div class="orange_block_two">
      <ul class="orange_wrapper">
        <li class="orange_img"></li>
        <li class="orange_item">ваш запрос</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "WorkOrange",
};
</script>

<style lang="scss" scoped>
.orange {
  display: flex;
  width: 100%;
  height: 181px;
  background: #f7654a;
}

.container {
  display: block;
  width: 567px;
  height: 9rem;
  padding-left: 1rem;
}

.orange_block_one {
  width: 50%;
  display: flex;
  align-items: center;
  justify-content: flex-end;
}

.orange_text_top {
  height: 67px;
  display: flex;
  font-family: "Oswald";
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 71px;
  letter-spacing: 0.02em;
  color: #ffffff;
  overflow: hidden;
}

.orange_text_bottom {
  display: flex;
  font-family: "Oswald";
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 36px;
  letter-spacing: 0.02em;
  color: #ffffff;
}

.orange_block_two {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 50%;
}

.orange_wrapper {
  display: flex;
  width: 175px;
  height: 49px;
  background: #ffffff;
  align-items: center;
  justify-content: center;
}

.orange_img {
  display: flex;
  background: url("../assets/block_tree/icon/message.png");
  background-size: cover;
  width: 18px;
  height: 12px;
  margin-right: 8px;
}

.orange_item {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 5rem;
  font-family: "Oswald";
  text-transform: uppercase;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 21px;
  letter-spacing: 0.05em;
  color: #000000;
}
</style>
