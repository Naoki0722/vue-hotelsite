<template>
  <!-- ConceptCard.vueを参考 -->
  <div class="title">
    <h2>CONCEPT</h2>
    <h3>感動で満ちあふれる<br>非日常を</h3>
    <p>この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。</p>
  </div>
</template>

<style scoped>
.title {
  width: 58%;
  margin: 10% auto 15%;
  text-align: center;
}

.title h2 {
  letter-spacing: 0.8rem;
}

.title h3 {
  padding: 3% 0 5%;
  font-size: 4.3rem;
  line-height: 6rem;
  color: #2c5e00;
  letter-spacing: 0.8rem;
  font-weight: 600;
}

.title p {
  font-size: 1.9rem;
  line-height: 2.8rem;
  color: gray;
}


/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .title {
    width: 90%;
  }
  .title h3 {
    font-size: 3.2rem;
    letter-spacing: 0.5rem;
  }
}

</style>