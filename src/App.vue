<template>
  <div id="app">
    <Home/>
    <Dialog :dialog="dialogA"/>
    <AboutMe/>
    <Work/>
    <Dialog :dialog="dialogB"/>
    <Footer/>
  </div>
</template>

<script>
import Home from '@/components/Home'
import Dialog from '@/components/Dialog'
import AboutMe from '@/components/AboutMe'
import Work from '@/components/Work'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: {
    Home,
    Dialog,
    AboutMe,
    Work,
    Footer
  },
  data () {
    return {
      dialogA: [
        'A: 你大學讀什麼呀?',
        '我: 我讀中興大學的土木工程。',
        'A: 那你來這邊幹嘛?',
        '我: ...'
      ],
      dialogB: [
        '因為喜歡...',
        '喜歡互動系韓秉軒老師多感官反饋與沈浸式虛擬',
        '實境的研究、王聖銘老師運用資料科學協助服務',
        '與行銷、陳圳卿老師分析使用者經驗於介面設計',
        '...',
        '因為喜歡，所以願意費盡努力去學習並且成就',
        '所以又為什麼要去限制我就應該去考結構技師',
        '土木技師或到什麼學校去。'
      ]
    }
  }
}
</script>

<style lang="scss">
body {
  margin: 0px;
  height: 100%;
}
#app {
  position: fixed;
  width: 100vw;
  height: 110vh;
  overflow-y: scroll;
  background-image: url("~@/assets/img/Background.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
}
</style>
