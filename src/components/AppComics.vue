<script>
export default{
    name: "AppComics",
}

</script>

<template>
    <div class="comics-container">

        <div class="content"> --> Content goes here <-- </div>

    </div>

  
 
</template>

<style lang="scss">

.comics-container{
    border: 1px solid red;
    /* test */
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;

    display: flex;
    justify-content: flex-start;
    align-items: center;

    .content{
        color: white;
        padding: 50px;
        font-weight: bolder;
        font-size: 30px;
    }

}
</style>