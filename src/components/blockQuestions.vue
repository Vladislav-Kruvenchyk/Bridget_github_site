<template>
  <div class="question">
    <div class="question_header">
      <h1 class="header_text">ответы на вопросы</h1>
    </div>

    <div class="question_wrap">
      <h1 class="question_list">РАБОТАЕТЕ ЛИ ВЫ ПО 249 ФЗ?</h1>
    </div>

    <div class="question_wrap">
      <h1 class="question_list">РАБОТАЕТЕ ЛИ ВЫ ПО 249 ФЗ?</h1>
    </div>

    <div class="question_box">
      <p class="question_item">
        Lorem Ipsum - это текст-"рыба", часто используемый в печати и
        вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на
        латинице с начала XVI века. В то время некий безымянный печатник создал
        большую коллекцию размеров и форм шрифтов, используя Lorem Ipsum для
        распечатки образцов.
      </p>
    </div>

    <div class="question_wrap">
      <h1 class="question_list">РАБОТАЕТЕ ЛИ ВЫ ПО 249 ФЗ?</h1>
    </div>

    <div class="question_wrap">
      <h1 class="question_list">РАБОТАЕТЕ ЛИ ВЫ ПО 249 ФЗ?</h1>
    </div>
  </div>
</template>

<script>
export default {
  nama: "Quaestion",
};
</script>

<style lang="scss" scoped>
.question {
  width: 100%;
  height: 614px;
  align-items: center;
}

.question_header {
  margin-top: 4rem;
  display: flex;
  width: 100%;
  height: 5rem;
  justify-content: center;
  align-items: center;
}

.header_text {
  text-align: center;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 53px;
  text-transform: uppercase;
  color: #000000;
}

.question_wrap {
  width: 50%;
  display: flex;
  margin-top: 2rem;
  justify-content: flex-end;
  padding-right: 10rem;
}

.question_list {
  display: flex;
  width: 20rem;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 36px;
  color: #f7654a;
}

.question_box {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
  padding-right: 14rem;
}
.question_item {
  width: 730px;
  height: 83px;
  overflow: hidden;
  font-family: "Open Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #999999;
}
</style>
