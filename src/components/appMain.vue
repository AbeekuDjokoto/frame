<template>
    <div >
        <h1>Minimize your tabs.<br>
            Find the trends!</h1>
        <p class="para">Don't let your computer memories consumes all of those browser tabs.
            Findtrend  let you gathers all of your favorite website into one place.</p>
        <div class="random">
            <app-button-vue text="Get Started 🔥" class="getStarted"></app-button-vue>
            <div class="arrowInfo">
                <p class="arrow">All research <br>
                start from here</p>
                <img src="@/assets/arrow.svg" alt="" srcset="">
            </div> 
        </div>
        <div class="fourCards">
            <appWavyVue></appWavyVue>

        </div>
        
    </div>
</template>

<script>
import appButtonVue from './appButton.vue'
import appWavyVue from './appWavy.vue'
export default {
    name: "appMain",
    components: { appButtonVue, appWavyVue },

}
</script>

<style scoped>


h1{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 900;
    font-size: 72px;
    line-height: 112%;
    /* identical to box height, or 81px */
    text-align: center;
    color: #FFFFFF;
    margin-top: 140px;
}

.para{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 150%;
    /* or 27px */
    text-align: center;
    color: #8B8B8B;
    margin: 24px 0px 40px 0px;
    width: 650px;
    margin-left: auto;
    margin-right: auto;
}

.random{
    text-align: center;
    display: flex;
    justify-content: center;
    margin-bottom: 96px;
}

.arrowInfo{
    margin-left: 18px;
}

.arrow{
    position: relative;
    top: -10px;
    color: white;
    transform: rotate(6deg);
    font-family: 'Caveat Brush', cursive;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 14px;
    text-align: center;
}

@media screen and (max-width: 375px) {
h1{
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    font-size: 36px;
    line-height: 112%;
}

.para{
    width: 286px;
    font-weight: 400;
    font-size: 14px;
    line-height: 150%;
    margin: 16px 0px 32px 0px;
    margin-left: auto;
    margin-right: auto;
}

.arrowInfo{
    display: none;
}
}

</style>