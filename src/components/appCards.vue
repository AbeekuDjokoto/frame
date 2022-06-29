<template>
    
    <div class="cards">
        <div>
            <figure>
                <img :src="imgSrc" alt=""/>
            </figure>
            <div class="info">
                <h2>{{ cardHeading }}</h2>
                <p>{{ cardSubheading }}</p>
            </div>

            <div class="latter">
                <button>{{ buttonInfo }}</button>
                <p>{{ price }}</p>
            </div>
        </div>
        
    </div>
</template>

<script scoped>
export default {
    name: "appCards",
    props: ["cardHeading", "cardSubheading", "imgSrc", "buttonInfo", "price"]
}
</script>

<style scoped>


.cards {
    background: #2E2E2E;
    box-shadow: 3px 5px 7px rgba(20, 20, 20, 0.2);
    border-radius: 4px;
    padding: 0px 0px 33px 0px;
    width: 444px;
    margin-bottom: 20px;    
}

.info{
    margin-bottom: 28px;
    margin-left: 20px;
    margin-top: 21px;
}

.info h2{
    margin-bottom: 18px;
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 20px;
    /* identical to box height, or 111% */
    letter-spacing: 1px;
    color: #E8E8E8;
}

.info p{
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 19px;
    /* or 136% */
    letter-spacing: 1px;
    color: #BBBBBB;
}

.latter{
    display: flex;
    justify-content: space-between;
    margin-left: 20px;
    margin-right: 33px;
}

button{
    background: #D91B42;
    border-radius: 4px;
    padding: 5px 10px;
    border: none;
}

.latter p{
    background: rgba(100, 100, 100, 0.1);
    border: 1px dotted #555555;
    border-radius: 4px;
    padding: 5px 10px;
    font-style: normal;
    font-weight: 400;
    font-size: 15px;
    line-height: 20px;
    /* identical to box height, or 133% */
    text-align: right;
    letter-spacing: 0.5px;
    color: #BBBBBB;
}
</style>