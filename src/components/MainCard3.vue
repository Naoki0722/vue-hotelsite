<template>
  <div class="maincard">
    <div class="main-img">
      <img src="../assets/crew-szCvt1gP2d4-unsplash.jpg" alt="メインカード3番目の画像">
    </div>
    <div class="text-area">
      <div class="main-text">
        <h2>ホテル専用のバーで<br>特別なひと時を</h2>
        <p>この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。</p>
        <ViewallButton />
      </div>
    </div>
  </div>
</template>


<script>
import ViewallButton from '../components/ViewallButton.vue'
export default {
  components: {
    ViewallButton
  }
}
</script>


<style scoped>
.maincard {
  background-color: rgb(247, 247, 247);
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 100px;
}

.main-img {
  width: 50%;
  text-align: right;
}

.main-img img {
  width: 80%;
  transform: translateY(-5%);
  box-shadow: -8px 8px 0px 0 rgb(187, 187, 187);
}

.text-area {
  width: 50%;
}

.main-text {
  padding: 0 10% 0 15%;
}

.main-text h2 {
  font-size: 3.5rem;
  letter-spacing: 4px;
  font-weight: 600;
  line-height: 40px;
}

.main-text p {
  padding: 4% 0;
  line-height: 30px;
}



/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */

  .maincard {
    display: block;
  }

  .main-img {
    width: 100%;
    text-align: left;
  }
  .text-area {
    width: 100%;
  }

  .main-text {
    padding: 3%;
  }

  .main-text h2 {
    font-size: 2.7rem;
  }
}

</style>