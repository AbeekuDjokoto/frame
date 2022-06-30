<template>
   <h1>Join us on email for <br>
    <span>more trending topics</span>
   </h1>
   <div class="move">
        <appButtonVue text="Join Now" class="joinNow"></appButtonVue>
   </div>
    
</template>

<script>
import appButtonVue from './appButton.vue'
export default {
 name: "lastButOne",
 components: { appButtonVue }
}
</script>

<style>

h1{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 900;
    font-size: 72px;
    line-height: 112%;
    /* identical to box height, or 81px */
    text-align: center;
    color: #000000;
}

span{
    font-family: 'Scope One', serif;
    font-style: normal;
    font-weight: 900;
    font-size: 72px;
    line-height: 112%;
    /* identical to box height, or 81px */
    text-align: center;
    color: #87D322;
}

.move{
    text-align: center;
    margin-top: 56px;
}
</style>