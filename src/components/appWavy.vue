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

@media screen and (max-width: 375px) {
.total{
    margin: 0px 90px 0px 0px;
    text-align: center;
    margin-left: 35px;
    margin-right: 35px;
}

.card{
    padding: 25px 13px 25px 25px;
    width: 293.04px;
    z-index: 1;
    box-shadow: 5px 5px 5px 5px black;
    margin-left: 0px;
    text-align: center;
}

p{
    font-size: 20.4445px;
    margin: 0px 3px 0px 13px; 
}

.secondCard {
    padding: 25px 13px 25px 25px;
    width: 292.3px;
    margin-top: auto;
    margin-left: auto;
}

.secondCard p{
    font-size: 20.393px;
    line-height: 24px;
    /* identical to box height */
    margin: 0px 3px 0px 11px; 
}

.test{
    margin: 0px; 
    text-align: center;
}

.thirdCard{
    position: relative;
    background: #181818;
    transform: rotate(-4deg);
    padding: 25px 13px 25px 25px;
    /* z-index: -1; */
    width: 293.04px;
    margin-right: auto;
    margin-left: auto;
}

.fourthCard{
    padding: 25px 13px 25px 25px;
    width: 293.04px;
    margin-right: auto;
    margin-left: auto;
    margin-top: 0px;
}

.fourthCard p{
    margin: 0px 3px 0px 11px; 
}

}

</style>