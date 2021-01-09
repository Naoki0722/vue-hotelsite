<template>
  <div class="newscard">
    <img src="../assets/window-3178666_1920 1.jpg" alt="ニュース画像">
    <p>COACHTECHの総生徒数が200名突破いたしました。</p>
  </div>
</template>

<style scoped>
.newscard {
  width: 23%;
}

.newscard img {
  width: 100%;
}

.newscard p {
  width: 95%;
  margin: 0 auto;
  padding: 5% 0;
}

/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .newscard {
    display: flex;
    width: 90%;
    justify-content: space-around;
    margin: 4% 0;
  }

  .newscard img {
    width: 40%;
    margin: 0 4%;
  }
}
</style>