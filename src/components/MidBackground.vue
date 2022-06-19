<template>
    <div class="midBackground">
        <img class="MidBackgroundSVG" src="../assets/MidBackground.svg" alt="mid-background-decoration">
        <div class="slides">
            <img src="../assets/cheesecake.jpg" alt="">
            <img src="../assets/oreo.jpg" alt="">
            <img src="../assets/red_velvet.jpg" alt="">
        </div>
    </div>
</template>
<script>
export default {
    name: 'MidBackgroundVue',
/*  components: {
        
    },*/
    data(){
        return {
            text1: 'JAJAJJA'
        }
    }
}
</script>
<style scoped>
    .midBackground{
        z-index: 2;
    }
    .slides{
        display: grid;
        grid-auto-flow: column;
        gap: 1rem;
        overflow-y: auto;
        overscroll-behavior-x: contain;
        scroll-snap-type: x mandatory;
        scrollbar-width: none;
    }
    .slides > img{
        scroll-snap-align: start;
    }
    .slides img{
        border-radius: 10px;
        width: 540px;
        height: 320px;
        object-fit: contain;
    }
    .slides::-webkit-scrollbar{
        display: none;
    }
</style>