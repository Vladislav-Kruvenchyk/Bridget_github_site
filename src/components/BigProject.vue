<template>
  <div class="projects">
    <div class="projects_wrapper">
      <ul class="projects_item">
        <li class="projects_list">лет</li>
        <li class="projects_list">лет</li>
        <li class="projects_list">лет</li>
        <li class="projects_list">лет</li>
      </ul>
    </div>

    <div class="projects_wrap">
      <ul class="projects_inner">
        <li class="projects_next">на рынке</li>
        <li class="projects_next">на рынке</li>
        <li class="projects_next">на рынке</li>
        <li class="projects_next">на рынке</li>
      </ul>
    </div>

    <div class="projects_title">
      <h1 class="project_title_text">наши самые большие проекты</h1>
    </div>

    <div class="project_content">
      <div class="container">
        <ul class="project_block">
          <li class="project_img"></li>
          <div class="project_bg">
            <div class="project_line"></div>
          </div>

          <div class="project_description">
            <h1 class="project_description_text">Газпром Арена</h1>
          </div>

          <div class="project_information">
            <p class="project_information_text">
              Мы сделали самую красивую арену в Европе. Это открытие стало для
              нас прорывной точкой для разивтия на следующие десятилетия. Мы
              очень рады данному еву.
            </p>
          </div>
        </ul>

        <div class="project_block_two">
          <li class="project_img"></li>
          <div class="project_bg">
            <div class="project_line"></div>
          </div>

          <div class="project_description">
            <h1 class="project_description_text">Газпром Арена</h1>
          </div>

          <div class="project_information">
            <p class="project_information_text">
              Мы сделали самую красивую арену в Европе. Это открытие стало для
              нас прорывной точкой для разивтия на следующие десятилетия. Мы
              очень рады данному еву.
            </p>
          </div>
        </div>

        <ul class="project_block_tree">
          <li class="project_img"></li>
          <div class="project_bg">
            <div class="project_line"></div>
          </div>

          <div class="project_description">
            <h1 class="project_description_text">Газпром Арена</h1>
          </div>

          <div class="project_information">
            <p class="project_information_text">
              Мы сделали самую красивую арену в Европе. Это открытие стало для
              нас прорывной точкой для разивтия на следующие десятилетия. Мы
              очень рады данному еву.
            </p>
          </div>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.projects {
  width: 100%;
  overflow: hidden;
}

.projects_wrapper {
  overflow: hidden;
  display: flex;
  width: 100%;
  justify-content: center;
}

.projects_item {
  background: #f7f7f7;
  display: flex;
  width: 1100px;
  height: 5rem;
  justify-content: center;
  align-items: center;
}

.projects_list {
  display: flex;
  width: 13rem;
  justify-content: center;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 53px;
  text-align: center;
  text-transform: uppercase;

  color: #000000;
}

.projects_wrap {
  display: flex;
  width: 100%;
  justify-content: center;
}

.projects_inner {
  background: #f7f7f7;
  display: flex;
  width: 1100px;
  height: 5rem;
  justify-content: center;
}
.projects_next {
  display: flex;
  width: 13rem;
  justify-content: center;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 27px;
  text-align: center;
  color: #999999;
}

.projects_title {
  display: flex;
  width: 100%;
  height: 10rem;
}
.project_title_text {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 6rem;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 53px;
  text-align: center;
  text-transform: uppercase;
  color: #404149;
}

.project_content {
  display: flex;
  width: 100%;
  justify-content: center;
  overflow: hidden;
}

.container {
  width: 1100px;
  display: flex;
  margin-top: 2rem;
  overflow: hidden;
  flex-shrink: 1;
  flex-wrap: wrap;
}

.project_block {
  display: flex;
  width: 350px;
  height: 681px;
  flex-direction: column;
  margin-top: 2rem;
}

.project_block_two,
.project_block_tree {
  margin-left: 1.5rem;
  display: flex;
  width: 350px;
  height: 681px;
  flex-direction: column;
  margin-top: 2rem;
}

.project_img {
  width: 350px;
  height: 380px;
  background: url("../assets/block_two/Rectangle 3.png");
  background-size: cover;
}

.project_img_two {
  width: 350px;
  height: 380px;
  margin-left: 1.5rem;
  background: url("../assets/block_two/Rectangle 3.png");
  background-size: cover;
}

.project_img_tree {
  width: 350px;
  height: 380px;
  margin-left: 1.5rem;
  background: url("../assets/block_two/Rectangle 3.png");
  background-size: cover;
}

.project_bg {
  display: flex;
  width: 100%;
  margin-top: 2rem;
}

.project_line {
  display: flex;
  width: 55px;
  height: 6px;
  background: #f7654a;
}

.project_description {
  display: flex;
  width: 350px;
  margin-top: 1rem;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 36px;
  color: #404149;
  overflow: hidden;
}

.project_description_text {
  display: flex;
  overflow: hidden;
  height: 3rem;
}
.project_information {
  display: flex;
  width: 350px;
}

.project_information_text {
  display: flex;
  overflow: hidden;
  width: 350px;
  height: 90px;
  margin-top: 1rem;
  font-family: "Open Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;

  color: #999999;
}
</style>
