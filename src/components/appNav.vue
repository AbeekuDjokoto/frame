<template>
  <header>
    <div>
        <figure>
            <img src="@/assets/IMAGE.svg" alt="" srcset="">
        </figure>
    </div>
    <nav>
        <ul>
            <li>Net Ninja Pro</li>
            <li>All Courses</li>
            <li>YouTube Channel</li>
            <li>Login</li>
            <li>Sign Up</li>
        </ul>
    </nav>
  </header>
</template>

<script>
export default {
    name: "appNav",
}
</script>

<style scoped>
header{
    background: #191919;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 40px 0px 40px;
}

ul{
    display: flex;
    gap: 0px 20px;
    list-style: none;
}

ul li{
    font-weight: 400;
    font-size: 13px;
    line-height: 20px;
    /* identical to box height, or 154% */
    letter-spacing: 0.5px;
    color: #FFFFFF;
}
</style>