<template>
  <div class="contacts">
    <div class="contact_header">
      <div class="text">контакты</div>
    </div>
    <div class="container">
      <div class="wrapper">
        <ul class="content">
          <li class="item_map"></li>
          <li class="item_contacts">АДРЕС:</li>
          <li class="item">НЕВСКИЙ ПРОСПЕКТ 140, <br />ОФИС 140-142</li>
        </ul>

        <ul class="content">
          <li class="item_phone"></li>
          <li class="item_contacts">ТЕЛЕФОН:</li>
          <li class="item">
            8 (812) 111-22-33 <br />
            8 (812) 111-22-33
          </li>
        </ul>

        <ul class="content">
          <li class="item_watch"></li>
          <li class="item_contacts">ВРЕМЯ РАБОТЫ:</li>
          <li class="item">
            ПН-СБ <br />
            10:00 - 20:00
          </li>
        </ul>

        <ul class="content">
          <li class="item_email"></li>
          <li class="item_contacts">E-MAIL:</li>
          <li class="item">INFO@VIP.RU</li>
        </ul>
      </div>
    </div>

    <div class="footer_block">
      <div class="footer_box">
        <p class="footer_text_left">© 2019 Строительная компания</p>
      </div>

      <div class="footer_box_two">
        <p class="footer_text_right">Разработано лучшей студей</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contacts",
};
</script>

<style lang="scss" scoped>
.contacts {
  width: 100%;
  height: 600px;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.contact_header {
  display: flex;
  margin-top: 7rem;
  width: 100%;
}

.text {
  display: flex;
  justify-content: center;
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
  margin-top: 2rem;
  width: 100%;
  height: 329px;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.wrapper {
  display: flex;
  width: 1100px;
  height: 310px;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}
.content {
  width: 15rem;
  height: 16rem;
  flex-direction: column;
  display: flex;
  align-items: center;
}

.item_map {
  background-size: cover;
  width: 38px;
  height: 57px;
  background: url("../assets/block_contacts/.png") no-repeat;
}

.item_contacts {
  display: flex;
  margin-top: 1rem;
  justify-content: center;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 36px;
  text-align: center;
  color: #999999;
}

.item {
  text-align: center;
  margin-top: 10px;
  font-family: "Oswald";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 36px;
  text-align: center;

  color: #000000;
}

.item_phone {
  background-size: cover;
  width: 50px;
  height: 57px;
  background: url("../assets/block_contacts/phone.png") no-repeat;
}

.item_watch {
  background-size: cover;
  width: 50px;
  height: 57px;
  background: url("../assets/block_contacts/watch.png") no-repeat;
}

.item_email {
  background-size: cover;
  width: 50px;
  height: 57px;
  background: url("../assets/block_contacts/email.png") no-repeat;
}

.footer_block {
  display: flex;
  width: 100%;
  height: 82px;
  align-items: center;
  background: #404149;
}

.footer_text_left {
  width: 50%;
}

.footer_text_right {
  width: 50%;
}

.footer_box {
  display: flex;
  justify-content: flex-end;
  font-family: "Open Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #ffffff;
}

.footer_box_two {
  display: flex;
  justify-content: center;
  padding-left: 4rem;
  font-family: "Open Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #ffffff;
}
</style>
