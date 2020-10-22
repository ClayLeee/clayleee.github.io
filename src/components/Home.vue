<template>
  <div class="home">
    <div class="navbar">
      <div class="navbar-portfolio">
        <img class="navbar-portfolio_white-people" src="../assets/img/home/white-people.png" alt="white-people"/>
        <img class="navbar-portfolio_big-title" src="../assets/img/home/portfolio.png" alt="portfolio"/>
      </div>
      <div class="navbar-dot">
        <img :src="greenDefault" alt="green">
        <img :src="yellowDefault" alt="yellow">
        <img :src="redDefault" alt="red">
        <!-- <img
          :src="greenDefault"
          @mouseover="greenDefault = greenLight"
          @mouseout="greenDefault = greenDot"
          alt="green"/>
        <img
          :src="yellowDefault"
          @mouseover="yellowDefault = yellowLight"
          @mouseout="yellowDefault = yellowDot"
          alt="yellow"/>
        <img
          :src="redDefault"
          @mouseover="redDefault = redLight"
          @mouseout="redDefault = redDot"
          alt="red"/> -->
      </div>
    </div>
    <div class="title">
      <img src="../assets/img/home/title-word1.png" alt="誤"/>
      <img
        :src="greenManDefault"
        @mouseover="greenManDefault = greenManGif"
        @mouseout="greenManDefault = greenMan"
        alt="入"/>
      <img
        :src="word3Default"
        @mouseover="word3Default = word3Change"
        @mouseout="word3Default = word3"
        alt="岐"/>
      <img src="../assets/img/home/title-word5.png" alt="途"/>
    </div>
    <div class="motto">
      <img src="../assets/img/home/motto.png" alt="motto"/>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      greenDefault: require('../assets/img/home/green.png'),
      // greenDot: require('../assets/img/home/green.png'),
      // greenLight: require('../assets/img/home/green-light.png'),
      yellowDefault: require('../assets/img/home/yellow.png'),
      // yellowDot: require('../assets/img/home/yellow.png'),
      // yellowLight: require('../assets/img/home/yellow-light.png'),
      redDefault: require('../assets/img/home/red.png'),
      // redDot: require('../assets/img/home/red.png'),
      // redLight: require('../assets/img/home/red-light.png'),
      greenManDefault: require('../assets/img/home/title-word2.png'),
      greenMan: require('../assets/img/home/title-word2.png'),
      greenManGif: require('../assets/img/home/greenman-walk.gif'),
      word3Default: require('../assets/img/home/title-word3.png'),
      word3: require('../assets/img/home/title-word3.png'),
      word3Change: require('../assets/img/home/title-word4.png')
    }
  }
}
</script>

<style lang="scss" scoped>
.home {
  width: 65%;
  margin: 50px auto 150px auto;
  .navbar {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    &-dot {
      position: relative;
      top: -40px;
    }
    &-portfolio {
      &_white-people {
        margin-right: 20px;
      }
      &_big-title {
        position: relative;
        top: 5px;
      }
    }
  }
  .title {
    width: 100%;
    margin: 100px auto;
    display: flex;
    justify-content: space-between;
  }
  .motto {
    margin-top: 150px;
    text-align: end;
  }
}
</style>
