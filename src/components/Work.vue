<template>
  <div class="work">
    <div class="title">
      <img src="../assets/img/work/work.png" alt="work">
    </div>
    <div class="works">
      <div class="item">
        <img src="../assets/img/work/work3.png" alt="work3">
        <div class="intro">
          <div class="title">程式與互動設計</div>
          <div class="list">
            <ol>
              <li>虛擬實境移動式充氣互動裝置設計</li>
              <li>大數據分析輿情觀察平台</li>
              <li>Micro:bit自動澆花紙水泥盆栽</li>
            </ol>
          </div>
        </div>
      </div>
      <div class="item">
        <div class="intro">
          <div class="title">產品設計與服務場域觀察</div>
          <div class="list">
            <ol>
              <li>橋樑結構檢測無人機</li>
              <li>士東市場服務場域觀察</li>
              <li>減碳遊戲APP UI 設計</li>
              <li>七月Bar無門桌遊設計</li>
              <li>I Go充電器設計</li>
              <li>參數化設計安全鼠籠</li>
            </ol>
          </div>
        </div>
        <img
          src="../assets/img/work/work2.png"
          alt="work2"
          @mouseover="isHovering = true"
          @mouseout="isHovering = false"
          :class="{hovering: isHovering}">
      </div>
      <div class="item">
        <img src="../assets/img/work/work3.png" alt="work3">
        <div class="intro">
          <div class="title">MV製作與多媒體藝術作品</div>
          <div class="list">
            <ol>
              <li>MV「那些失眠的夜與難忘的夜晚製作」</li>
              <li>AE無透視立體動畫</li>
              <li>Apophysis碎形藝術圖像創作</li>
            </ol>
          </div>
        </div>
      </div>
      <div class="item">
        <div class="intro">
          <div class="title">其他作品</div>
          <div class="list">
            <ol>
              <li>土木專題橋樑設計</li>
              <li>中興大學藝術季帆布袋 與A5水壺設計</li>
              <li>系服設計</li>
              <li>產品Sketch</li>
            </ol>
          </div>
        </div>
        <img src="../assets/img/work/work4.png" alt="work4">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      isHovering: false
    }
  }
}
</script>

<style lang="scss" scoped>
.work {
  width: 65%;
  margin: 0 auto;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 5px;
  .title {
    margin-bottom: 50px;
  }
  .item {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    margin-bottom: 80px;
    .hovering {
      opacity: 0.7;
      cursor: pointer;
    }
    .intro {
      width: 230px;
      .list {
        font-size: 15px;
      }
    }
  }
}
</style>
