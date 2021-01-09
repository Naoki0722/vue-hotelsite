<template>
  <div class="viewallbotton">
    <div class="background-gray"></div>
    <div class="main-button">View All</div>
  </div>
</template>

<style scoped>
.viewallbotton {
  position: relative;
  width: 130px;
  height: 50px;
  border-bottom: 1px solid rgb(173, 173, 173);
}

.viewallbotton:after {
  content: '';
  width: 10px;
  height: 30px;
  position: absolute;
  right: 5%;
  bottom: -10%;
  border-left: 1px solid rgb(173, 173, 173);
  transform: rotate(-70deg);
}

.background-gray {
  background-color: rgb(173, 173, 173);
  position: absolute;
  top: 0;
  bottom: 0;
  width: 50px;
}

.main-button {
  position: absolute;
  top: 50%;
  left: 15%;

}
</style>