<template>
    <footer>
        <div class="infoFooter">
            <h3>&copy; Net Ninja 2022</h3>
            <ul>
                <li><a href="#">Net Ninja on Twitter</a></li>
                <li><a href="#">Net Ninja on YouTube</a></li>
                <li><a href="#">Get Net Ninja Pro</a></li>
            </ul>
        </div>
        <div class="addInfo">
            <ul>
                <li><a href="#">Terms of Service</a></li>
                <li><a href="#">Privacy Policy</a></li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'appFooter'
}
</script>

<style scoped>
footer{
    display: flex;
    justify-content: space-between;
    padding: 17px 120px 20px 120px;
    background: #252525;
    border-radius: 0px;
}

.infoFooter h3{
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 20px;
    /* identical to box height, or 111% */
    color: #FFFFFF;
    margin-bottom: 13px;
}

.infoFooter ul{
    text-decoration: none;
    list-style-type: none;
    display: block;
}

.infoFooter ul li a{
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    /* identical to box height, or 143% */
    letter-spacing: 0.5px;
    color: #777777;
    text-decoration: none;
} 


.addInfo ul{
    text-decoration: none;
    list-style-type: none;
    display: block;
}

.addInfo ul li a{
    text-decoration: none;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    /* identical to box height, or 143% */
    letter-spacing: 0.5px;
    color: #777777;
}
</style>