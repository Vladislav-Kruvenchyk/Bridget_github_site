<template>
  <div class="partners">
    <div class="partners_header">
      <h1 class="partners_text">наши партнеры</h1>
    </div>

    <div class="partners_box">
      <div class="partners_img"></div>
      <div class="partners_img"></div>
      <div class="partners_img"></div>
      <div class="partners_img"></div>
      <div class="partners_img"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Partners",
};
</script>

<style lang="scss" scoped>
.partners {
  // display: flex;
  width: 100%;
  height: 364px;
  background: #404149;
}

.partners_header {
  display: flex;
  width: 100%;
  height: 11rem;
  align-items: flex-end;
  justify-content: center;
  text-align: center;
}

.partners_text {
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 53px;
  text-transform: uppercase;
  color: #ffffff;
}

.partners_box {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  flex-shrink: 1;
  margin-top: 2rem;
}

.partners_img {
  display: flex;
  margin-left: 3rem;
  margin-right: 2rem;
  width: 170px;
  height: 61px;
  background: url("../assets/block_partners/image.png");
  background-size: cover;
}
</style>
