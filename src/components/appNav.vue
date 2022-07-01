<template>
  <header>
    <div class="header">
        <div class="heroLogo">
                <img src="@/assets/Vector.svg" alt="" srcset="">
                <p>Findtrend</p>
        </div>
    <nav>
        <ul>
            <li>About</li>
            <li>How it works</li>
            <li>Pricing</li>
            <li>Solution</li>
            <li>Features</li>
        </ul>
    </nav>

    
    <div class="display">
        <span class="login">Login</span>
        <app-button-vue text="Register"></app-button-vue>
    </div>
        
    </div>
  </header>
</template>

<script>
import appButtonVue from './appButton.vue'
export default {
    name: "appNav",
    components: { appButtonVue },
}
</script>

<style scoped>
.header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 28px 80px 0px 80px;
}

.heroLogo{
    align-items: center;
    text-align: center;
    display: flex;
}

p{
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 100%;
    /* identical to box height, or 24px */
    text-align: center;
    color: #FFFFFF;
    margin-left: 10px;
}

ul{
    display: flex;
    gap: 0px 20px;
    list-style: none;
}

ul li{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 100%;
    /* identical to box height, or 18px */
    text-align: center;
    color: #FFFFFF;
}

.login{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 100%;
    /* identical to box height, or 18px */
    text-align: center;
    color: #FFFFFF;
    margin-right: 40px;
}

@media screen and (max-width: 375px) {
.header{
    padding: 24px 80px 0px 18px;
}

ul, .display{
    display: none;
}
}



</style>