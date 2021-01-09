<template>
  <div class="title">
    <h2>HOW TO ENJOY</h2>
    <h3>楽しみ方</h3>
  </div>
</template>

<style scoped>
.title {
  width: 58%;
  margin: 10% auto 0;
  text-align: center;
}

.title h2 {
  letter-spacing: 0.8rem;
}

.title h3 {
  padding: 3% 0 5%;
  font-size: 4.3rem;
  line-height: 6rem;
  color: #220e01;
  letter-spacing: 0.8rem;
  font-weight: 600;
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