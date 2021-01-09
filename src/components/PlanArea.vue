<template>
  <div class="title">
    <h2>STAY PLAN</h2>
    <h3>おすすめの宿泊プラン一覧</h3>
    <div class="hotel-card">
      <PlanCard />
      <PlanCard />
      <PlanCard />
    </div>
    <div class="sm-hotel-card">
      <carousel :per-page="1" v-bind:autoplay="true"  v-bind:loop="true">
        <slide>
          <PlanCard />
        </slide>
        <slide>
          <PlanCard />
        </slide>
        <slide>
          <PlanCard />
        </slide>
      </carousel>
    </div>
  </div>
</template>

<script>
import PlanCard from './PlanCard'
export default {
  components: {
    PlanCard,

  }
}
</script>

<style scoped>

.title {
  width: 100%;
  margin: 30% auto;
  text-align: center;
}

.title h2 {
  letter-spacing: 0.8rem;
}

.title h3 {
  padding: 3% 0 3%;
  font-size: 4.3rem;
  line-height: 6rem;
  color: #220e01;
  letter-spacing: 0.8rem;
  font-weight: 600;
}

.hotel-card {
  display: flex;
  justify-content:space-around;
}

.sm-hotel-card {
  display: none;
}
/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .title {
    width: 98%;
  }
  .title h3 {
    font-size: 2.8rem;
    letter-spacing: 0.1rem;
  }
  .hotel-card {
    display: none;
  }
  .sm-hotel-card {
    display: block;
  }
}

</style>