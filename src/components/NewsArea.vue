<template>
  <div class="news">
    <!-- ConceptCard.vueを参照 -->
    <div class="title">
      <h2>NEWS</h2>
      <h3>ニュース</h3>
      <p>サンプルテキストが入ります。ここにはサンプルテキストが入ります。</p>
      <div class="pc-button">
        <ViewallButton />
      </div>
    </div>
    <NewsCard />
    <NewsCard />
    <NewsCard />
    <div class="sm-button">
      <ViewallButton />
    </div>
  </div>
</template>


<script>
import NewsCard from './NewsCard.vue'
import ViewallButton from './ViewallButton.vue'
export default {
  components: {
    NewsCard,
    ViewallButton
  }
}
</script>
<style scoped>
.news {
  display: flex;
  justify-content: space-between;
  background-color: rgb(247, 247, 247);
  padding: 5% 0;
}
.title {
  margin-left: 5%;
  width: 18%;
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

.title p {
  color: rgb(168, 166, 166);
  line-height: 2rem;
  padding-bottom: 20px;
}


.sm-button {
  display: none;
}



/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .pc-button {
    display: none;
  }
  .title {
    width: 90%;
  }
  .title h3 {
    font-size: 3.2rem;
  }
  .news {
    display: block;
  }

  .sm-button {
    display: block;
    height: 50px;
    position: relative;
  }

  .viewallbotton {
    position: absolute;
    right: 4%;
    bottom: -3%;
  }
}
</style>