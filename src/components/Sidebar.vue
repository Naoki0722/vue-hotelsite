<template>
  <div class="side">
    <div class="main">
      <div class="hamburger">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
    <div class="search">
      <p>空室検索</p>
    </div>
  </div>
</template>

<style scoped>
.side {
  width: 8%;
  height: 100%;
  position: fixed;
  z-index: 10;
  top: 0;
  left: 0;
}

.main {
  background-color: #C4C4C4;
  height: 75%;
}

.hamburger {
  background-color: green;
  position: relative;
}

.hamburger span {
  position: absolute;
  display: block;
  width: 30%;
  left: 30%;
  background-color: white;
  height: 2px;
  border-radius: 10%;
}
.hamburger span:nth-child(1) {
  top: 10px;
}
.hamburger span:nth-child(2) {
  top: 25px;
}
.hamburger span:nth-child(3) {
  top: 40px;
}


.search {
  height: 25%;
}

.search p {
  writing-mode: vertical-rl;
  padding: 10% 25%;
  position: relative;
  margin: 20% auto;
  font-size: 1.9rem;
  letter-spacing: 1rem;

}

.search p:before,
.search p:after {
	content: '';
	width: 10%;
	height: 10%;
	position: absolute;
} 

.search p:before {
  border-right: 1px solid gray;
  border-top: 1px solid gray;
  top: 0;
  right: 0;
}

.search p:after {
  border-left: 1px solid gray;
  border-bottom: 1px solid gray;
  bottom: 0;
  left: 0;
}

/* デザインA（スマホ） */
/* スマホ用レイアウト 599px以下の範囲に収めるデザインはこの中に記述 */
@media screen and (max-width: 599px) {
  .main {
    display: none;
  }
  .search {
    position: fixed;
    bottom: 0;
    right: 0;
    z-index: 10;
    background-color: white;
    box-shadow: 0 10px 25px 0 rgba(0, 0, 0, .5);
    width: 60%;
    height: 80px;
  }

  .search p {
    writing-mode: horizontal-tb;
    padding: 30px 10%;
    margin: auto;
    text-align: center;
    font-size: 2rem;
    color: rgb(66, 30, 1);
  }

  .search p:before,
  .search p:after {
    content: '';
    width: 30px;
    height: 30px;
    position: absolute;
  } 

  .search p:before {
    border-right: 1px solid gray;
    border-top: 1px solid gray;
    top: 5%;
    right: 5%;
  }

  .search p:after {
    border-left: 1px solid gray;
    border-bottom: 1px solid gray;
    bottom: 5%;
    left: 5%;
  }
}
</style>