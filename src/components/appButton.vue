<template>
    <button class="baseColor">{{text}}</button>
</template>

<script>
export default {
    name: "AppButton",
    props: ["text"]
};
</script>

<style scoped>
.baseColor{
        padding: 12px 32px;
        background: #FFFFFF;
        border-radius: 40px;
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 100%;
        /* identical to box height, or 18px */
        text-align: center;
        color: #000000;
        border: none;
        font-family: 'Scope One', serif;
    }

.getStarted{
    padding: 16px 32px;
    font-family: 'Scope One', serif;
    background: #A8FF35;
    border-radius: 40px;
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    line-height: 140%;
    /* or 25px */
    text-align: center;
}

.blackElon{
    background: #030303;
    padding: 25px 23px;
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 23.8064px;
    line-height: 28px;
    /* identical to box height */
    text-align: center;
    color: #FFFFFF;
}

.blackButton{
    padding: 16px 32px;
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    line-height: 140%;
    /* or 25px */
    text-align: center;
    color: #FFFFFF;
    background: #000000;
    border-radius: 40px;
    margin-top: 40px;
}

.startFreeTrial{
    padding: 17px 88px;
    background: #A8FF35;
    border-radius: 29px;
    font-style: normal;
    font-weight: 700;
    font-size: 15px;
    line-height: 140%;
    /* or 25px */
    text-align: center;
    color: #000000;
}

.joinNow{
    background: #000000;
    border-radius: 40px;
    padding: 16px 52px;
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    line-height: 140%;
    /* or 25px */
    text-align: center;
    color: #FFFFFF;
}


</style>