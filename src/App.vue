<template>
  <div id="app">
    <Sidebar />
    <Bottombar />
    <div class="main-menu">
      <FirstView />
      <MainConcept />
      <MainCard />
      <MainCard2 />
      <MainCard3 />
      <MainCard4 />
      <EnjoyArea />
      <PlanArea />
      <NewsArea />
      <Reservation />
      <Access />
      <Footer />
      <!-- テストエリア -->
      <!-- <PlanCard /> -->
      
    </div>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import Bottombar from './components/Bottombar.vue'
import FirstView from './components/FirstView.vue'
import MainConcept from './components/MainConcept.vue'
import MainCard from './components/MainCard.vue'
import MainCard2 from './components/MainCard2.vue'
import MainCard3 from './components/MainCard3.vue'
import MainCard4 from './components/MainCard4.vue'
import EnjoyArea from './components/EnjoyArea.vue'
import PlanArea from './components/PlanArea.vue'
import NewsArea from './components/NewsArea.vue'
import Reservation from './components/Reservation.vue'
import Access from './components/Access.vue'
import Footer from './components/Footer.vue'
// テスト
// import PlanCard from './components/PlanCard.vue'

export default {
  name: 'App',
  components: {
    Sidebar,
    Bottombar,
    FirstView,
    MainConcept,
    MainCard,
    MainCard2,
    MainCard3,
    MainCard4,
    EnjoyArea,
    PlanArea,
    NewsArea,
    Reservation,
    Access,
    Footer
    // テスト
    // PlanCard
    
  }
}
</script>

<style>

/* 左サイド */



/* 本コンテンツ */

.main-menu {
  position: absolute;
  width: 92%;
  left: 8%;
}







/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .main-menu {
    /* position: relative; */
    width: 100%;
    left: 0;
  }
}





/*
html5doctor.com Reset Stylesheet
v1.6.1
Last Updated: 2010-09-17
Author: Richard Clark - http://richclarkdesign.com
Twitter: @rich_clark
*/

html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

html {
  font-size: 62.5%;
}

body {
    line-height:1;
    font-size: 1.6em;
    font-family: "Times New Roman", "YuMincho", "Hiragino Mincho ProN", "Yu Mincho", "MS PMincho", serif;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}
</style>