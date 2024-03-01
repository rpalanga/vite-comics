<script>
import AppMain from './AppMain.vue';



export default {

    name: "AppComics",


    components: {
        AppMain
    }


}

</script>

<template>
    <div class="comics-container">

        <div class="comics">

            <div class="content"> Content goes here </div>

        </div>
    </div>

    <AppMain />
    
</template>

<style lang="scss">
.comics-container {
    width: 100%;

    margin-left: auto;
    margin-right: auto;

    background-color: black;

}

.comics {

    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;

    display: flex;
    justify-content: flex-start;
    align-items: center;

    .content {
        color: white;
        padding: 50px;
        font-weight: bolder;
        font-size: 30px;
    }

}
</style>