<template>
  <header>
    <div class="header">
        <div class="heroLogo">
                <img src="@/assets/blackLogo.svg" alt="" srcset="">
                <p>Findtrend</p>
        </div>


        <nav class="footerNav">
            <ul>
                <li>Privacy Policy</li>
                <li>Terms and Conditions</li>
                <li>Contact Us</li>
                <li>Careers</li>
            </ul>
        </nav>
    
        
    </div>
  </header>
</template>

<script>

export default {
    name: "appNav",
}
</script>

<style scoped>
.header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 29px 80px 29px 80px;
    background: white;
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
    color: #000000;
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
    color: #000000;
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
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    padding: 62px 0px 80px 0px;
    background: white;
}

.heroLogo{
    margin-left: 62px;
    margin-bottom: 99px;
}

ul{
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    gap: 40px 0px;
    list-style: none;
    text-align: center;
}

.footerNav{
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}
}


</style>