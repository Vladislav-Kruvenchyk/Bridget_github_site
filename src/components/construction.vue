<template>
  <div class="construction">
    <!-- <div class="construction_header">
            <div class="text">чем мы занимаемся</div>
        </div> -->
    <div class="container">
      <div class="construction_header">
        <h1 class="text">чем мы занимаемся</h1>
      </div>
      <div class="container_footer">
        <div class="content">
          <ul class="wrapper">
            <li class="item"></li>
          </ul>

          <ul class="wrapper">
            <li class="item"></li>
          </ul>

          <ul class="wrapper">
            <li class="item"></li>
          </ul>

          <ul class="wrapper">
            <li class="item"></li>
          </ul>

          <ul class="wrapper">
            <li class="item"></li>
          </ul>

          <ul class="wrapper">
            <li class="item"></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Constructor",
};
</script>

<style lang="scss" scoped>
.construction {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.construction_header {
  display: flex;
  margin-top: 5rem;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 53px;
  text-transform: uppercase;
  color: #000000;
}

.text {
  height: 5rem;
  text-align: center;
}
.container {
  display: block;
  width: 100%;
  text-align: center;
  overflow: hidden;
}

.container_footer {
  display: flex;
  width: 100%;
  justify-content: center;
  overflow: hidden;
}
.content {
  overflow: hidden;
  width: 1110px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.wrapper {
  display: flex;
  margin-top: 6rem;
  width: 350px;
  height: 250px;
  background: #f7f7f7;
  align-items: center;
  justify-content: center;
  margin-left: 1rem;
}

.item {
  display: flex;
  width: 172px;
  height: 132px;
  justify-content: center;
  background: url("../assets/block_construction/Group.png");
  background-size: cover;
}
</style>
