<template>
    <div class="hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div>
</template>

<style scoped>
/* デザインA（スマホ） */
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
@media screen and (max-width: 599px) {
  /* .bottom {
    position: fixed;
    bottom: 10%;
    z-index: 10;
  } */
  .hamburger {
    position: fixed;
    bottom: 1%;
    left: 5%;
    z-index: 10;
    background-color: gray;
    width: 70px;
    height: 70px;
    border-radius: 50%;
  }
  .hamburger span {
    position: absolute;
    display: block;
    width: 45%;
    height: 2px;
    left: 50%;
    transform: translateX(-50%);
    background-color: white;
  }
  .hamburger span:nth-child(1) {
    top: 15px;
  }
  .hamburger span:nth-child(2) {
    top: 30px;
  }
  .hamburger span:nth-child(3) {
    top: 45px;
  }
}
</style>