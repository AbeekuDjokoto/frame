<template>
  <div>
    <AppNav></AppNav>  
  </div>
  
  <main>
    <div class="main">
      <AppCards v-for="card in cards" 
    :key="card.id"
    :imgSrc="card.url" 
    :cardHeading="card.title" 
    :cardSubheading="card.subTitle" 
    :buttonInfo="card.courseInfo" 
    :price="card.price">
  
      </AppCards>
    </div>
    <div class="courses">
      <AppButton text="View All Courses"></AppButton>
    </div>
    <AppFooter></AppFooter>
  </main>
</template>

<script>
import AppButton from "./components/appButton.vue";
import AppNav from "./components/appNav.vue";
import AppCards from "./components/appCards.vue";
import AppFooter from "./components/appFooter.vue";
export default {
    name: 'App',
    components: { AppButton, AppNav, AppCards, AppFooter },
    data(){
      return{
        cards: [
          {id: "1a", url: require('@/assets/1.svg'), title: "Net Ninja Pro", subTitle: "Access all courses in the Net Ninja Pro library, extra courses not available on YouTube & all Premium Udemy courses too. Plus early access to bew Courses.", courseInfo: "51 Course Bundle", price: "$9/month"},
          {id: "2a", url: require('@/assets/fireBase.svg'), title: "Build Websites with React & Firebase", subTitle: "Learn how to make dynamic websites using React and Firebase, from the ground up.", courseInfo: "41 Course Bundle", price: "$9"},
          {id: "3a", url: require('@/assets/html.svg'), title: "HTML & CSS Crash Course", subTitle: "Learn the fundamentals of HTML & CSS & start your web development journey from here.", courseInfo: "31 Course Bundle", price: "$8"},
          {id: "4a", url: require('@/assets/node.svg'), title: "Node.js Crash Course", subTitle: "Learn all about Node.js (from the very beginning) & how to use it to power the back-end of websites using JavaScript.", courseInfo: "21 Course Bundle", price: "$7"},
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
  background: #212121;
  border-radius: 0px;
}

.main{
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  margin: 48px 0px 48px 0px;
}

.courses{
  text-align: center;
  margin-bottom: 80px;
}


</style>