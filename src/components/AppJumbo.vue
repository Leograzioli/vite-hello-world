<script>
export default {
    data() {
        return {
            myImage: "vue.svg"
        }
    },
    methods: {
        getPathImg() {
            return new URL(`../assets/${this.myImage}`, import.meta.url).href;
        }
    }
}
</script>

<template>
    <img :src="getPathImg()" alt="">
</template>

<style>

</style>