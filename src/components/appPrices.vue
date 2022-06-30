<template>
    <div class="enclosure">
    <div class="cards" v-for="card in cards" 
        :key="card.id" 
        :id="card.id"
        :style="[card.isTrue === true ? {background: '#A8FF35' } : 'none' ]">
        <div class="personal">
            <h1>{{ card.title }}</h1>
            <p>{{ card.subTitle }}</p>
        </div>
            <div class="space">
                <p class="para">{{card.price }}</p>
                <p class="month">{{ card.month }}</p>
            </div>
        <div class="para">
            <p>{{ card.text1 }}</p>
            <p>{{ card.text2 }}</p>
            <p>{{ card.text3 }}</p>
            <p>{{ card.text4 }}</p>
            <p>{{ card.text5 }}</p>
            <p>{{ card.text6 }}</p>
            <p>{{ card.text7 }}</p>
        </div> 
        <app-button-vue text="Start Free Trial" class="startFreeTrial"></app-button-vue>
    </div>
</div>
</template>

<script scoped>
import appButtonVue from './appButton.vue'
export default {
    name: "priceCards",
    props: ["title", "subTitle", "price", "month", "text1", "text2", "text3", "text4", "text5", "text6", "text7" ],
    components: { appButtonVue },
    data(){
        return{
            cards: [
                {id: "1a", title: "Personal", subTitle: "Special first packet for all", price: "$8", month: "/Month", text1: "✓ Up to 5 page each group", text2: "✓ Up to 10 group page", text3: "✓ 5 Days group page saved", text4: "", text5: "", text6: "", text7: "", },
                {id: "2a", title: "Regular", subTitle: "Recommended for personal pro", price: "$20", month: "/Month", text1: "✓ Up to 15 page each group", text2: "✓ Download page up to 20 page", text3: "✓ Up to 10 group page", text4: "✓ 15 Days group page saved", text5: "", text6: "", text7: "",  isTrue: true},
                {id: "3a", title: "Premium", subTitle: "Packet for Startup & Company", price: "$48", month: "/Month", text1: "✓ Up to 5 page each group", text2: "✓ Up to 10 group page", text3: "✓ 5 Unlimited download page", text4: "✓ Unlimited page each group", text5: "✓ Customize group page name", text6: "✓ Customize group page name", text7: "✓ 30 Days group page saved", },
            ]
        }
    }
}
</script>

<style scoped>
.enclosure{
    display: flex;
    justify-content: space-evenly;
    padding: 40px 0px 140px 0px;
    background: #000000;
}

.cards {
    background: #F5F5F5;
    border-radius: 8px;
    padding: 32px 32px;
    width: 360px;
}

.personal h1{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 36px;
    line-height: 100%;
    /* identical to box height, or 36px */
    color: #000000;
    margin-bottom: 8px;
}

.personal p{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 100%;
    /* identical to box height, or 18px */
    color: #000000;
    margin-bottom: 64px;
}

hr{
    padding: 32px;
}

.space{
    margin-bottom: 35px;
    display: flex;
}

.space .para{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 64px;
    line-height: 100%;
    /* identical to box height, or 64px */
    color: #000000;
}

.space .month{
    padding-top: 30px;
}


.para p{
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 100%;
    color: #000000;
    margin-bottom: 30px;
}

</style>