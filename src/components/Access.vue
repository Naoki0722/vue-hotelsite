<template>
  <div class="access">
    <div class="mapimage">
      <img src="../assets/スクリーンショット 2020-12-09 15.05 1.jpg" alt="アクセスマップ">
    </div>
    <!-- ConceptCard.vueを参照 -->
    <div class="title">
      <h2>ACCESS</h2>
      <h3>アクセス</h3>
      <p class="postal">〒163-8001<br>東京都新宿区西新宿2丁目8-1</p>
      <p class="tell-number"><font-awesome-icon icon="phone" />0120-000-0000</p>
      <p class="email"><font-awesome-icon icon="envelope" />info@hotel.com</p>
      <p class="station">「JR新宿駅」（西口から徒歩約10分）<br>都営地下鉄大江戸線「都庁前駅」</p>
    </div>
  </div>
</template>

<style scoped>
.access {
  display: flex;
  align-items: center;
  justify-content: center;
}


.title {
  width: 58%;
  margin: 0 auto;
  text-align: left;
  padding-left: 5%;
}

.title h2 {
  letter-spacing: 0.8rem;
}

.title h3 {
  padding: 3% 0 5%;
  font-size: 4.3rem;
  line-height: 6rem;
  color: #220e01;
  font-weight: 600;
}

.postal,
.tell-number,
.email,
.station {
  font-size: 2rem;
  line-height: 3rem;
  margin: 3% 0;
}


/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .title {
    width: 90%;
    margin-top: 5%;
    padding: 0;
  }
  .title h3 {
    font-size: 3.2rem;
  }
  .access {
    display: block;
    margin-bottom: 15%;
  }
  .mapimage {
    width: 100%;
  }
  .mapimage img {
    width: 100%;
  }
  .station {
    margin-bottom: 10%;
  }
}
</style>