<template>
    <button>{{text}}</button>
</template>

<script>
export default {
    name: "AppButton",
    props: ["text"]
};
</script>

<style scoped>
button{
        padding: 15px 30px;
        font-size: 12px;
        border: 1px solid #444444;
        border-radius: 4px;
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
        /* identical to box height, or 150% */
        text-align: center;
        letter-spacing: 1px;
        color: #BBBBBB;
        background-color: #444444;
        /* margin-bottom: 80px; */
    }
</style>