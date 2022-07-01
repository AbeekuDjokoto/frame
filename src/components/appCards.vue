<template>
    
    <div class="cards">
        <div>
            <figure>
                <img :src="imgSrc" alt=""/>
            </figure>

        </div> 
    </div>

</template>

<script scoped>
export default {
    name: "appCards",
    props: ["imgSrc"]
}
</script>

<style scoped>

.cards {
    background: #F5F5F5;
    border-radius: 8px;
    padding: 20px 28px;
    text-align: center;
    width: 266px;
    margin-right: 32px;   
    margin-bottom: 32px;   
}

@media screen and (max-width: 375px) {
.cards {
    background: #F5F5F5;
    border-radius: 8px;
    padding: 20px 23px;
    text-align: center;
    width: 162px;
    margin-right: 15px;   
    margin-bottom: 15px;   
}

img{
    width: 100px;
}
}

</style>