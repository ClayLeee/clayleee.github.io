<template>
  <div class="about-me">
    <div class="about-me-title">
      <img src="../assets/img/aboutme/about-me.png" alt="about-me">
    </div>
    <div class="intro">
      <div class="big-head">
        <img class="front" src="../assets/img/aboutme/big-head.png" alt="big-head">
        <img class="back" src="../assets/img/aboutme/yellow-block.png" alt="yellow-block">
      </div>
      <div class="sub-intro">
        <span style="width: 300px;">HI!我是林庭伃,</span>
        <span style="width: 420px;">大學畢業於中興大學土木工程學系,</span>
        <span style="width: 290px;">高中就讀曉明女子中學。</span>
        <span>我是叛逆執著於設計的工程師,希望整合自身</span>
        <span>人文與邏輯思維能力,深入互動設計領域學習。</span>
      </div>
    </div>
    <div class="expertise">
      <div class="expertise-title title">專長</div>
      <div class="expertise-content">
        <div>軟體語言</div>
        <div>
          <ul>
            <li>C#(Unity)</li>
            <li>Python</li>
          </ul>
        </div>
        <div>開發工具</div>
        <div>
          <ul>
            <li>Unity</li>
            <li>Arduino</li>
            <li>Micro:bit</li>
          </ul>
        </div>
        <div>軟體技能</div>
        <div>
          <ul>
            <li>Adobe AI/ PS/</li>
            <li>AE</li>
            <li>Rhino / Keyshot</li>
            <li>Autocad/</li>
            <li>Sketchup</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="experience">
      <div class="experience-title title">活動經歷</div>
      <div class="experience-content">
        <div class="block">
          <div class="item">
            <div class="middle">2019興鮮人-設計部部長 2019.2-2019.9</div>
            <div class="small">負責整體活動主視覺設計、迎新手冊、海報的設計、訂製等，為全校性的迎新</div>
          </div>
          <div class="item">
            <div class="middle">2018興大藝術季-視覺部部長 2017.11-2018.5</div>
            <div class="small">統籌跨部門合作、活動主視覺設計</div>
          </div>
          <div class="item">
            <div class="middle">2018興大藝術季-參展人 2017.11-2018.5</div>
            <div class="small">概念發想、企劃、空間規劃</div>
          </div>
          <div class="item">
            <div class="middle">興大圖書館參考組-美術編輯</div>
            <div class="small">負責圖書館各式文物平面視覺設計</div>
          </div>
        </div>
        <div class="block">
          <div class="item">
            <div class="middle">中興大學西畫社-社長 2017.9-2018.6</div>
            <div class="small">統籌成果發表、電腦繪圖、人體素描等課程</div>
          </div>
          <div class="item">
            <div class="middle">中興大學長虹吉他社-副社長</div>
            <div class="small">協助舉辦各種社團活動、活動企劃、友校表演、義演</div>
          </div>
          <div class="item">
            <div>中興大學長虹吉他社-迎新總召 2017.7-2017.10</div>
          </div>
          <div class="item">
            <div>中興大學長虹吉他社-成發主持人 2017.11-2017.12</div>
          </div>
        </div>
      </div>
    </div>
    <div class="other">
      <div class="other-left">
        <div class="research">
          <div class="title">學術研究</div>
          <div class="item">
            <div class="middle">具腦機介面控制之互動式上之復健系統平台暨復健資料庫系統支開發</div>
            <div class="small">2020.7-202011 協助VR遊戲互動系統開發</div>
          </div>
        </div>
        <div class="language">
          <div class="title">語言能力</div>
          <div class="item">
            <div class="middle">英文-多益795分</div>
            <div class="middle">德文-基礎</div>
            <div class="middle">台語-流暢</div>
          </div>
        </div>
      </div>
      <div class="other-right">
        <div class="contest">
          <div class="title">參賽經歷</div>
          <div class="block">
            <div class="item">
              <div class="middle">全國大專院校盃原創桌上遊戲設計比賽-決賽入圍</div>
              <div class="small">2018.12 遊戲機制發想、平面視覺產出、道具製作</div>
            </div>
            <div class="item">
              <div class="middle">2020 LEXUS 設計大賞-初賽入選</div>
              <div class="small">概念發想、機構設計、建模</div>
            </div>
            <div class="item">
              <div class="middle">中興土木抗震盃競賽 2017.4-2017.5</div>
              <div class="small">負責結構設計、抗震測試</div>
            </div>
            <div class="item">
              <div class="middle">第十四屆 晟銘盃</div>
              <div class="small">概念發想、草圖、機構設計、建模</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.item {
  height: 50px;
  margin-bottom: 15px;
  .middle {
    font-size: 18px;
    letter-spacing: 1px;
  }
  .small {
    font-size: 15px;
    letter-spacing: 1px;
    color: #bab7b7;
  }
}

.title {
  font-size: 23px;
  display: inline;
  padding: 0 20px;
  color: #ffc854;
  border: 1px solid #ffc854;
}
.about-me {
  width: 65%;
  margin: 150px auto;
  color: #ffffff;
  letter-spacing: 5px;
  .intro {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 150px;
    .big-head {
      position: relative;
      top: -120px;
      .front {
        position: absolute;
        z-index: 10;
        left: 20px;
        top: 20px;
      }
      .back {
        position: absolute;
        z-index: 5;
      }
    }
    .sub-intro {
      display: flex;
      flex-direction: column;
      position: relative;
      top: 10px;
      > span {
        background: #ffc854;
        padding-left: 10px;
        font-size: 20px;
        &:first-child {
          font-size: 30px;
        }
        &:nth-child(n):not(:last-child) {
          margin-bottom: 10px;
        }
      }
    }
  }
  .expertise {
    margin-bottom: 50px;
    &-content {
      margin-top: 20px;
      display: flex;
      flex-direction: row;
      justify-content: space-evenly;
      align-items: center;
    }
  }
  .experience {
    margin-bottom: 50px;
    &-content {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      margin-top: 20px;
    }
  }
  .other {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    &-left {
      .research {
        margin-bottom: 60px;
        .item {
          margin-top: 20px;
        }
      }
      .language {
        .item {
          margin-top: 20px;
        }
      }
    }
    &-right {
      position: relative;
      right: 100px;
      .contest {
        .block {
          margin-top: 20px;
        }
      }
    }
  }
}
</style>
