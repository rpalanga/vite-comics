<script>
import AppJumbotron from './AppJumbotron.vue';



export default {

    name: "AppJumbotron",


   


}

</script>

<template>

    <div class="container-jumbotron">
        <img id="jumbo" src="../../public/img/jumbotron.jpg" alt="">

        <div id="series-jumbo">
            CURRENT SERIES
        </div>
    </div>



</template>

<style lang="scss">
.container-jumbotron{
    position: relative;


    #series-jumbo{
        
        color: white;
        background-color: #3880F1;
        padding: 10px;
        text-transform: uppercase;
        font-weight: bolder;
        font-size: 20px;


        position: absolute;
        left: 80px;
        transform: translateY(-50%);
    }


    #jumbo{
        width: 100vw;
        height: 400px;
        object-fit: cover;
        object-position: top;
        display: block;
    }
}


</style>