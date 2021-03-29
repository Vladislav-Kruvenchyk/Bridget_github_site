<template>
  <div class="riviews">
    <div class="riviews_header">
      <div class="riviews_block">
        <h1 class="riviews_text">отзывы о работе с нами</h1>
      </div>
    </div>

    <div class="container">
      <div class="block">
        <div class="content">
          <div class="wrapper">
            <div class="box">
              <div class="img"></div>
              <span class="text">
                Lorem Ipsum - это текст-"рыба", часто используемый в печати и
                вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для
                текстов на латинице с начала XVI века. В то время некий
                безымянный печатник создал большую коллекцию размеров и форм
                шрифтов.
              </span>
            </div>
          </div>
          <div class="wrapper">
            <div class="box">
              <div class="img"></div>
              <span class="text">
                Lorem Ipsum - это текст-"рыба", часто используемый в печати и
                вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для
                текстов на латинице с начала XVI века. В то время некий
                безымянный печатник создал большую коллекцию размеров и форм
                шрифтов.
              </span>
            </div>
          </div>

          <div class="wrapper">
            <div class="box">
              <div class="img"></div>
              <span class="text">
                Lorem Ipsum - это текст-"рыба", часто используемый в печати и
                вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для
                текстов на латинице с начала XVI века. В то время некий
                безымянный печатник создал большую коллекцию размеров и форм
                шрифтов.
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer_content">
      <div class="footer_block_two">
        <div class="inner">
          <p class="footer_text">Иванов Иван,</p>
          <p class="text_orange">ООО “Газпром-Арена”</p>
        </div>
      </div>

      <div class="footer_block_two">
        <div class="inner">
          <p class="footer_text">Иванов Иван,</p>
          <p class="text_orange">ООО “Газпром-Арена”</p>
        </div>
      </div>

      <div class="footer_block_two">
        <div class="inner">
          <p class="footer_text">Иванов Иван,</p>
          <p class="text_orange">ООО “Газпром-Арена”</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Riviews",
};
</script>

<style lang="scss" scoped>
.riviews {
  width: 100%;
  height: 635px;
}

.riviews_header {
  display: flex;
  width: 100%;
  height: 10rem;
}
.riviews_text {
  display: flex;
  justify-content: center;
  height: 5rem;
}
.riviews_block {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 53px;
  text-transform: uppercase;

  color: #000000;
}

.container {
  display: flex;
  width: 100%;
  justify-content: center;
}

.content {
  display: flex;
  justify-content: center;
}
.block {
  display: block;
  width: 100%;
  height: 260px;
  justify-content: center;
  align-items: center;
}

.box {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.wrapper {
  display: flex;
  margin-left: 1rem;
  margin-right: 1rem;
  width: 350px;
  height: 259px;
  justify-content: center;
  align-items: center;
  background: #f7f7f7;
}

.img {
  display: flex;
  margin-right: 15rem;
  width: 42px;
  height: 32px;
  background: url("../assets/block_riviews/img.png");
  background-size: cover;
}

.text {
  display: flex;
  width: 290px;
  align-items: center;
  margin-top: 1rem;
  font-family: "Open Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 21px;
  color: #999999;
  height: 142px;
  overflow: hidden;
}

.footer_content {
  display: flex;
  width: 100%;
  justify-content: center;
  margin-top: 2rem;
}

.footer_block_two {
  display: flex;
  width: 350px;
  margin-left: 1rem;
  margin-right: 1rem;
}
.inner {
  display: flex;
  width: 350px;
}

.footer_text,
.text_orange {
  display: flex;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 21px;
  line-height: 31px;
  letter-spacing: 0.02em;
  width: 8rem;
  color: #000000;
}

.text_orange {
  display: flex;
  width: 13rem;
  color: #f7654a;
}
</style>
