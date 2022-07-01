<template>
  <div class="main">
    <h1>Findtrend helps you to increase your 
productivity and reduce your computer's 
memory load, <span>an application that can 
fulfill your daily browsing needs.</span> </h1>

<h1 class="finder">Findtrend make +1000 Startup grow</h1>
  </div>
</template>

<script>
export default {
    name: "FindTred"
}
</script>

<style scoped>

.main{
    padding: 140px 0px 80px 0px;
    background: #FFFFFF;
}

h1{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 700;
    font-size: 54px;
    line-height: 76px;
    /* identical to box height */
    color: #000000;
    text-align: left;
}

span{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 700;
    font-size: 54px;
    line-height: 76px;
    /* identical to box height */
    color: #ADADAD;
}

.finder{
    margin-top: 280px;
}

@media screen and (max-width: 375px) {
.main{
    padding: 80px 18px 32px 18px;
    background: #FFFFFF;
    text-align: center
}

h1{
    font-weight: 900;
    font-size: 36px;
    line-height: 43px;
    flex-wrap: wrap;
}

span{
    font-weight: 900;
    font-size: 36px;
    line-height: 43px;
}

.finder{
    margin-top: 160px;
    text-align: center
}


}
</style>