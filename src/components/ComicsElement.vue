<script>
export default {
    name: "ComicsElement",

    props: {

        ComicsImg: String,
        ComicsName: String

    }
}
</script>

<template>
    <div id="comics-element">
        <img :src="ComicsImg" alt="">
        <h3>{{ ComicsName }}</h3>

    </div>
</template>

<style lang="scss">

#comics-element{
            width: calc(100% / 6 - 10px / 6 * 5);
            padding-top:30px;
            padding-bottom:30px;
            
    
            img{
                width: 180px;
                height: 180px;
                object-fit: cover;
                object-position: top;
            }
        }

</style>