<template>
  <div class="maincard-2">
    <div class="sm-main-img">
      <img src="../assets/carlos-machado-TmRckxjJoP8-unsplash.jpg" alt="メインカード2番目の画像">
    </div>
    <div class="text-area">
      <div class="main-text">
        <h2>大自然を見渡せる<br>プライベートプール付き</h2>
        <p>この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。</p>
        <ViewallButton />
      </div>
    </div>
    <div class="main-img">
      <img src="../assets/carlos-machado-TmRckxjJoP8-unsplash.jpg" alt="メインカード2番目の画像">
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
.maincard-2 {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 100px;
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

.main-img {
  width: 50%;
}

.main-img img {
  width: 80%;
}

.sm-main-img {
  display: none;
}

/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .main-img {
    display: none;
  }
  .maincard-2 {
    display: block;
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
  .sm-main-img {
    display: block;
    text-align: right;
  }
  .sm-main-img img {
    width: 85%;
  }
}

</style>