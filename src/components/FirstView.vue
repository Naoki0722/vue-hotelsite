<template>
  <header>
    <div class="first-img">
      <img src="../assets/window-3178666_1920 1.jpg" alt="トップ画像">
    </div>
    <div class="first-title">
      <h2>感動はここにある</h2>
    </div>
  </header>
</template>

<style scoped>

header {
  position: relative;
}

.first-title h2 {
  position: absolute;
  width: 100%;
  text-align: center;
  top: 50%;
  /* left: 50%;
  transform: translateX(-50%) translateY(-50%); */
  color: white;
  font-size: 6.5rem;
  letter-spacing: 1rem;
  font-weight: 600;
}

.first-img {
  background-color: #000;
}

.first-img img{
  display: block;
  opacity: .7;
  width: 100%;
  height: 700px;
  object-fit: cover;
}


/* デザインA（スマホ） */
@media screen and (max-width: 599px) {
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
  .first-title h2 {
    font-size: 4.5rem;
    letter-spacing: 0.5rem;
  }
}
</style>