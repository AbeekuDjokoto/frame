<template>
<div>
    
</div>
    <div class="total">
        <div class="card">
            <img src="@/assets/imagesss.svg" alt="" srcset="">
            <p>Cryptopunk - Search</p>
            <p><img src="@/assets/Group1.svg" alt="" srcset=""></p>
        </div>
        <div class="secondCard">
            <img src="@/assets/popularDesign.svg" alt="" srcset="">
            <p>Popular Design</p>
            <p><img src="@/assets/Group1.svg" alt="" srcset=""></p>
        </div>
    </div>
    <div class="test">
        <div class="thirdCard">
            <img src="@/assets/favebook.svg" alt="" srcset="">
            <p>Product Design</p>
            <p><img src="@/assets/Group1.svg" alt="" srcset=""></p>
        </div>
    </div> 
    <div class="fourthCard">
            <img src="@/assets/ball.svg" alt="" srcset="">
            <p>Elon Musk - Search</p>
            <p><img src="@/assets/Group1.svg" alt="" srcset=""></p>
    </div>
    <div class="pad"></div>
            
</template>

<script>
export default {
    name: "wavyCards",
}
</script>

<style scoped>
.total{
    margin: 0px 90px 0px 106px;
}

.card{
    position: relative;
    background: #181818;
    transform: rotate(-4deg);
    padding: 29px 33px;
    display: flex;
    width: 366.23px;
    z-index: 1;
    box-shadow: 5px 5px 5px 5px black;
}

p{
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 23.8065px;
    line-height: 28px;
    /* identical to box height */
    text-align: center;
    color: #FFFFFF;
    align-items: center;
    margin: 0px 3px 0px 13px; 
}

.secondCard {
    /* position: relative; */
    background: #181818;
    transform: rotate(2deg);
    display: flex;
    align-items: center;
    padding: 29px 33px;
    width: 370.23px;
    margin-top: -30px;
    margin-left: 190px;
}

.secondCard p{
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 23.8065px;
    line-height: 28px;
    /* identical to box height */
    text-align: center;
    color: #FFFFFF;
    align-items: center;
    margin: 0px 3px 0px 13px; 
}

.test{
    display: flex;
    margin: -150px 0px 0px 539px; 
}
.thirdCard{
    position: relative;
    background: #181818;
    transform: rotate(-4deg);
    padding: 29px 33px;
    display: flex;
    width: 366.23px;
    /* z-index: -1; */
    box-shadow: 5px 5px 5px 5px black;
}

.fourthCard{
    background: #181818;
    transform: rotate(2deg);
    display: flex;
    align-items: center;
    padding: 29px 33px;
    width: 360.23px;
    margin-top: -30px;
    margin-left: 797px;
}

.pad{
    padding-bottom: 99px;
}

</style>