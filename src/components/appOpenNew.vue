<template>
  <main>
    <div>
        <h1>Open new tabs is sh*t</h1>
        <img src="@/assets/Group427.svg" alt="" class="arrow">
        <div class="enclosure">
            <div class="card">
                <img src="@/assets/Group16.svg" alt="">
                <span>Findtrend - Elon Musk</span>
                <img src="@/assets/Group1.svg" alt="">
            </div>
        </div>
        <img src="@/assets/Group428.svg" alt="" class="arrow2">
        
        <div class="para">
            <p>A solution for your browser tabs and don't make your device get slower over time. Get <br>
                ease and faster to discover a trend with just one tab.</p>
        </div>  
        
        
    </div>
    
  </main>
</template>

<script>

export default {
    name: "OpenNew",
}
</script>

<style scoped>

main{
    background: #A8FF35;
    padding: 140px 0px; 
}

h1{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 700;
    font-size: 72px;
    line-height: 86px;
    /* identical to box height */
    text-align: center;
    color: #000000;
    margin-bottom: 60px;
}

.arrow{
    position: relative;
    top: 150px;
    left: 240px;
}

.arrow2{
    position: relative;
    left: 920px;
    bottom: 150px;
}
.enclosure{
    padding: 60px 80px;
    margin-left: auto;
    margin-right: auto;
    width: 502px;
    background: #F5F5F5;
    border-radius: 16px;
}
.card{
    background: #030303;
    align-items: center;
    padding: 27px 30px;
    width: 360px;
}

span{
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 23.8064px;
    line-height: 28px;
    /* identical to box height */
    text-align: center;
    color: #FFFFFF;
    margin: 0px 10px 0px 10px;
}

.para{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 150%;
    /* or 27px */
    text-align: center;
    color: #000000;
    margin-top: 60px;
}

@media screen and (max-width: 375px) {
h1{
    font-size: 36px;
    line-height: 112%;
    margin-bottom: 32px;
}

.arrow{
    top: 190px;
    left: 10px;
    transform: rotate(-17.64deg);
}
.enclosure{
    padding: 24px;
    margin-left: auto;
    margin-right: auto;
    width: 339px;
    border-radius: 14px;
    align-items: center;
}

.arrow2{
    position: relative;
    left: 280px;
    bottom: 185px;
    transform: rotate(-25.64deg);
}
.card{
    /* padding: 27px 30px; */
    padding: 22px 22px;
    width: 291px;
    align-items: center;
}

span{
    font-size: 18.3023px;
    line-height: 24px;
    /* identical to box height */
    text-align: center;
    color: #FFFFFF;
    margin: 0px 3px 0px 3px;
    align-items: center;
}

.para{
    font-size: 14px;
    line-height: 150%;
    margin-top: 34px;
}


}
</style>