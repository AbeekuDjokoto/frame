<template>
  <div class="header">
    <AppNav></AppNav>
    <app-main></app-main> 
  </div>
  
  <main>
    <AppOpenNewVue></AppOpenNewVue>
    <appFindTrendVue></appFindTrendVue>
    <div class="main">
      <AppCards v-for="card in cards" 
    :key="card.id"
    :imgSrc="card.url">
      </AppCards>
    </div>
    <div class="section">
      <h1>All platform connect to Findtrend</h1>
    <div class="courses">
      <AppElonMuskVue v-for="card in anotherCards" 
      :key="card.id"
      :imgSrc="card.url"
      :style="[card.green === 0 ? {background: '#A8FF35' } : 'none' ]"
      :id="card.id"></AppElonMuskVue>
    </div>
    <AppImageElon></AppImageElon>
  </div>
  <div>
    <AppPrices></AppPrices>
  </div>
  <div class="last">
    <AppAlmostLastVue></AppAlmostLastVue>
  </div>
    <!-- <AppFooter></AppFooter> -->
  </main>
  
  
</template>

<script>
import AppButton from "./components/appButton.vue";
import AppNav from "./components/appNav.vue";
import AppCards from "./components/appCards.vue";
import AppFooter from "./components/appFooter.vue";
import AppMain from "./components/appMain.vue";
import AppMainVue from "./components/appMain.vue";
import AppOpenNewVue from "./components/appOpenNew.vue";
import appFindTrendVue from "./components/appFindTrend.vue";
import AppElonMuskVue from "./components/appElonMusk.vue";
import AppImageElon from "./components/appImageElon.vue";
import AppPrices from "./components/appPrices.vue";
import AppAlmostLastVue from "./components/appAlmostLast.vue";
export default {
    name: 'App',
    components: { AppButton, AppNav, AppCards, AppFooter, AppMain, AppMainVue, AppOpenNewVue, appFindTrendVue, AppElonMuskVue, AppImageElon, AppPrices, AppAlmostLastVue },
    data(){
      return{
        cards: [
          {id: "1a", url: require('@/assets/image116.svg')},
          {id: "2a", url: require('@/assets/image128.svg')},
          {id: "3a", url: require('@/assets/image121.svg')},
          {id: "4a", url: require('@/assets/image119.svg')},
          {id: "5a", url: require('@/assets/image125.svg')},
          {id: "6a", url: require('@/assets/image122.svg')},
          {id: "7a", url: require('@/assets/image133.svg')},
          {id: "8a", url: require('@/assets/image129.svg')},
          {id: "9a", url: require('@/assets/image117.svg')},
          {id: "10a", url: require('@/assets/image126.svg')},
          {id: "11a", url: require('@/assets/image120.svg')},
          {id: "12a", url: require('@/assets/image124.svg')},
          {id: "13a", url: require('@/assets/image132.svg')},
          {id: "14a", url: require('@/assets/image127.svg')},
          {id: "15a", url: require('@/assets/image118.svg')},
          {id: "16a", url: require('@/assets/image130.svg')},
        ],
        anotherCards: [
          {id: "1aa", url: require('@/assets/image105.svg')},
          {id: "2aa", url: require('@/assets/image96.svg'), green: 0},
          {id: "3aa", url: require('@/assets/Rectangle6.svg')},
          {id: "4aa", url: require('@/assets/image111.svg')},
          {id: "5aa", url: require('@/assets/image113.svg')},
          {id: "6aa", url: require('@/assets/image114.svg')},
          {id: "7aa", url: require('@/assets/image115.svg')},
          {id: "7aa", url: require('@/assets/image112.svg')},
        ]
        
      }
    }
}
</script>

<style>

*{
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
}

body{
  /* background: #212121; */
  border-radius: 0px;
}

.header{
  background-image: url(./assets/Bg-hero.svg);
}

.main{
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  margin: 0px 0px 48px 0px;
  background: #FFFFFF;
}

.courses{
  display: flex;
  margin: 80px 0px 77px 0px;
}
.section{
  background: #FAFAFA;
  padding: 140px 140px 140px 140px;
  text-align: center;
  margin-left: auto; 
}

.section h1{
  font-family: 'Scope One', serif;
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 76px;
  /* identical to box height */
  text-align: center;
  color: #000000;
  padding: 140px 0px 80px 0px;
  font-family: 'Scope One', serif;
}

.last{
  padding: 140px 0px;
  background: #A8FF35;
}


</style>