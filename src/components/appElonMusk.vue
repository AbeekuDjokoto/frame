<template>
        
        <div class="cards">
            
            <figure>
                <img :src="imgSrc" alt=""/>
            </figure>

        </div> 


</template>

<script scoped>
export default {
    name: "appCards",
    props: ["imgSrc", "style"]
}
</script>

<style scoped>

/* template{
    
} */

.cards {
    background: #FFFFFF;
    border-radius: 8px; 
    padding: 32px;  
    margin-right: 10px;
}

.gCard {
    background: #A8FF35;
    border-radius: 8px; 
    padding: 32px;
}
</style>