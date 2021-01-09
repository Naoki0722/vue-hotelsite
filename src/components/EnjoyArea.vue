<template>
  <div class="enjoy-area">
    <!-- ConceptCard.vueを参考 -->
    <ConceptCard />
    <div class="imagecard-area">
      <ImageCard />
      <ImageCard2 />
    </div>
  </div>
</template>

<script>
import ConceptCard from './ConceptCard.vue'
import ImageCard from './ImageCard.vue'
import ImageCard2 from './ImageCard2.vue'
export default {
  components: {
    ConceptCard,
    ImageCard,
    ImageCard2
  }
}
</script>


<style scoped>

.imagecard-area {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}


/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .imagecard-area {
    padding: 0 5%;
  }

}

</style>