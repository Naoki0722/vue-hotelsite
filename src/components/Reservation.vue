<template>
  <!-- ConceptCard.vueを参照 -->
  <div class="reserve-area">
    <div class="title">
      <h2>RESERVATION</h2>
      <h3>ご予約</h3>
    </div>
    <InfoTell />
  </div>
</template>

<script>
import InfoTell from './InfoTell.vue'
export default {
  components: {
    InfoTell
  }
}
</script>

<style scoped>
.reserve-area {
  margin-bottom: 100px;
}

.title {
  width: 58%;
  margin: 20% auto 0;
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
  }
}

</style>