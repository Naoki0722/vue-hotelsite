<template>
  <div class="card">
    <img src="../assets/window-3178666_1920 1.jpg" alt="宿泊プラン">
    <div class="text-area">
      <p>【スペシャルプライスプラン】岳和洋室2ベッド 禁煙 露天風呂付/2食付き</p>
      <div class="button-area">
        <button>プラン詳細はこちら</button>
      </div>
    </div>
  </div>
</template>

<style scoped>

.card {
  background-color: rgb(247, 247, 247);
  width: 25%;
}

.card img {
  width: 100%
}


.text-area p {
  padding: 5% 4%;
  line-height: 2.4rem;
  letter-spacing: 0.6rem;
  text-align: left;
}

.button-area {
  text-align: center;
}

.button-area button {
  font-size: 1.6rem;
  background-color: black;
  color: white;
  padding: 8px 15px;
  margin-bottom: 4%;
}

/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .card {
    width: 80%;
    margin: 0 auto;
  }
}
</style>