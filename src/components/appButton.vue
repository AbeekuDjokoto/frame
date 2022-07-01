<template>
    <button class="baseColor">{{text}}</button>
</template>

<script>
export default {
    name: "AppButton",
    props: ["text"],
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
    font-family: 'Scope One', serif;
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
    font-family: 'Scope One', serif;
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

@media screen and (max-width: 375px) {
.getStarted{
    padding: 12px 24px;
    font-size: 14px;
}

.blackButton{
    padding: 12px 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 140%;
    margin-top: 32px;
}

.startFreeTrial{
    padding: 15px 80px;
    border-radius: 27.3083px;
    font-weight: 700;
    font-size: 17px;
    line-height: 140%;
}

.joinNow{
    padding: 12px 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 140%;
}
}


</style>