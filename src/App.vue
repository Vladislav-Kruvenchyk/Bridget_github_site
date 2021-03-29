<template>
  <div id="app">
    <vHeader />
    <vBigProject />
    <vOrange />
    <vConstruction />
    <vImg />
    <vQuestion />
    <vPartners />
    <vRiviews />
    <vWorkOrange />
    <vContacts />
  </div>
</template>

<script>
import vHeader from "./components/header";
import vBigProject from "./components/BigProject";
import vOrange from "./components/orangeSmart";
import vConstruction from "./components/construction";
import vImg from "./components/img";
import vQuestion from "./components/blockQuestions";
import vPartners from "./components/partners";
import vRiviews from "./components/riviews";
import vWorkOrange from "./components/workOrange";
import vContacts from "./components/contacts";

export default {
  components: {
    vHeader,
    vBigProject,
    vOrange,
    vConstruction,
    vImg,
    vQuestion,
    vPartners,
    vRiviews,
    vWorkOrange,
    vContacts,
  },
};
</script>

<style lang="scss">
* {
  width: 100%;
  height: auto;
  overflow-x: hidden;
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  text-decoration: none;
  outline: none;
}

body::-webkit-scrollbar {
  width: 1em;
  background: #fff;
  /* display: none; */
}

body::-webkit-scrollbar-track {
  box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
}

body::-webkit-scrollbar-thumb {
  background-color: #f7654a;
  outline: 1px solid slategrey;
}

@font-face {
  font-family: "Oswald";
  src: url("./assets/fonst/Oswald_one/fonts/Oswald-VariableFont_wght.eot");
  src: local("☺"),
    url("./assets/fonst/Oswald_one/fonts/Oswald-VariableFont_wght.woff")
      format("woff"),
    url("./assets/fonst/Oswald_one/fonts/Oswald-VariableFont_wght.ttf")
      format("truetype"),
    url("./assets/fonst/Oswald_one/fonts/Oswald-VariableFont_wght.svg")
      format("svg");
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: "Open Sans";
  src: url("./assets/fonst/Open Sanse/fonts/open_sans.eot"); /* IE 9 Compatibility Mode */
  src: url("./assets/fonst/Open Sanse/fonts/open_sans.ttf")
      format("embedded-opentype"),
    /* IE < 9 */ url("./assets/fonst/Open Sanse/fonts/open_sans.woff2")
      format("woff2"),
    /* Super Modern Browsers */
      url("./assets/fonst/Open Sanse/fonts/open_sans.woff") format("woff"),
    /* Firefox >= 3.6, any other modern browser */
      url("./assets/fonst/Open Sanse/fonts/open_sans.svg") format("svg"); /* Chrome < 4, Legacy iOS */
}
</style>
