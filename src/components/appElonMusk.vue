<template>
        
        <div class="cards" v-for="card in cards" 
      :key="card.id"
      :id="card.id"
      :style="[card.isTrue === true ? {background: '#A8FF35' } : 'none' ]">
            <img :src="card.url" alt="">
      </div> 


</template>

<script scoped>
export default {
    name: "appCards",
    props: [ "style", "title"],
    data(){
        return{
            cards: [
                {id: "1aa", url: require('@/assets/image105.svg')},
                {id: "2aa", url: require('@/assets/image96.svg'), isTrue: true},
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

<style scoped>

.cards {
    background: #FFFFFF;
    border-radius: 8px; 
    padding: 32px;  
    margin-right: 10px;
}

.gCard {
    background: #A8FF35;
    border-radius: 8px; 
    padding: 32px;
}

@media screen and (max-width: 375px) {
.cards {
    background: #FFFFFF;
    border-radius: 8px; 
    padding: 16px;  
    margin-right: 10px;
    width: 64px;
}

img{
    width: 30px;
}
}

</style>