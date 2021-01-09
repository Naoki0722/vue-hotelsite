<template>
  <footer>
    <nav class="pc-navigation">
      <div class="flex nav-list-1">
        <li><font-awesome-icon icon="caret-right" />ガイド</li>
        <li><font-awesome-icon icon="caret-right" />採用情報</li>
      </div>
      <div class="flex nav-list-2">
        <li><font-awesome-icon icon="caret-right" />私たちについて</li>
        <li><font-awesome-icon icon="caret-right" />よくある質問</li>
      </div>
      <div class="flex nav-list-3">
        <li><font-awesome-icon icon="caret-right" />お知らせ</li>
        <li><font-awesome-icon icon="caret-right" />お問い合わせ</li>
      </div>
      <div class="flex nav-list-4">
        <li><font-awesome-icon icon="caret-right" />アクティビティ</li>
        <li><font-awesome-icon icon="caret-right" />プライバシーポリシー</li>
      </div>
    </nav>
    <nav class="sm-navigation">
        <li><font-awesome-icon icon="caret-right" />ガイド</li>
        <li><font-awesome-icon icon="caret-right" />私たちについて</li>
        <li><font-awesome-icon icon="caret-right" />お知らせ</li>
        <li><font-awesome-icon icon="caret-right" />アクティビティ</li>
        <li><font-awesome-icon icon="caret-right" />採用情報</li>
        <li><font-awesome-icon icon="caret-right" />よくある質問</li>
        <li><font-awesome-icon icon="caret-right" />お問い合わせ</li>
        <li><font-awesome-icon icon="caret-right" />プライバシーポリシー</li>
    </nav>
    <div class="divider">
    </div>
    <div class="footer-text">
      <small>©︎COACHTECH Inc. All Rights Reserved.</small>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: black;
  color: white;
}
.pc-navigation li {
  list-style: none;
}
.pc-navigation {
  display: flex;
  justify-content: center;
}

.sm-navigation {
  display: none;
}
.flex {
  margin: 5% 2% 0;
}
.flex li {
  margin-bottom: 30px;
  font-size: 2rem;
}

.divider {
  width: 85%;
  margin: 2% auto 0;
  height: 2px;
  background-color: white;
}

.footer-text {
  width: 95%;
  text-align: center;
  padding: 3% 0;
}

/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .pc-navigation {
    display: none;
  }
  .sm-navigation {
    display: block;
    padding: 10% 5%;
  }
  .sm-navigation li {
    list-style: none;
    padding: 3% 5%;
    font-size: 2rem;
  }



  .footer-text {
    margin-bottom: 80px;
  }
}
</style>