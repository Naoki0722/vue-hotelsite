<template>
  <div class="tellcard">
    <div class="tellnumber">
      <div class="icon">
        <font-awesome-icon icon="phone" />
      </div>
      <div class="number">
        <p class="tell">TEL 0120-000-000</p>
        <p class="time">受付 10:00~19:00</p>
      </div>
    </div>
    <div class="reserve-button">
      <button>宿泊のご予約はこちら</button>
    </div>
  </div>  
</template>

<style scoped>
.tellcard {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: rgb(247, 247, 247);
  width: 60%;
  margin: 0 auto;
  text-align: center;
  padding: 4% ;

}

.tellnumber {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50%;
  margin-right: 20%;
}

.icon {
  font-size: 4.5rem;
  margin-right: 3%;
}
.tell {
  font-size: 3rem;
}

.time {
  text-align: left;
  color: gray;
}

.reserve-button {
  width: 60%;
}

.reserve-button button {
  font-size: 2.5rem;
  background-color: black;
  color: white;
  padding: 5% 10%;
  
}

/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .tellcard {
    display: block;
    width: 90%;
  }
  .icon {
    font-size: 3rem;
  }
  .tell {
    font-size: 2.8rem;
  }
  .tellnumber {
    width: 100%;
    margin: 10% auto;
  }
  .reserve-button {
    width: 100%;
    margin: 10% auto;
  }
}
</style>