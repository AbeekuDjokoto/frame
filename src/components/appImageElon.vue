<template>
  <div>
    <figure>
        <img src="@/assets/tweet1.svg" alt="">
    </figure>
    <figure>
        <img src="@/assets/tweet2.svg" alt="">
    </figure>
    <figure>
        <img src="@/assets/tweet3.svg" alt="">
    </figure>
    <app-button-vue text="View More Trends" class="blackButton"></app-button-vue>
  </div>
</template>

<script>
import appButtonVue from './appButton.vue'
export default {
    name: "ElonMusk",
    components: { appButtonVue }
}
</script>

<style scoped>

figure{
    text-align: center;
    align-items: center;
    margin-bottom: 40px;
}
</style>