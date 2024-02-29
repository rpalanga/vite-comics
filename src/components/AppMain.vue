<script>
export default {
    name: "AppMain",

    data() {
        return {
            objects: [
                {
                    name: "DIGITAL COMICS",
                    img: "../../public/img/buy-comics-digital-comics.png"
                },
                {
                    name: "DC MERCHANDISE",
                    img: "../../public/img/buy-comics-merchandise.png"
                },
                {
                    name: "SUBSCRIPTION",
                    img: "../../public/img/buy-comics-subscriptions.png"
                },
                {
                    name: "COMIC SHOP LOCATOR",
                    img: "../../public/img/buy-comics-shop-locator.png"
                },
                {
                    name: "DC POWER VISA",
                    img: "../../public/img/buy-dc-power-visa.svg"
                }
            ]
        }
    }

}

</script>

<template>
    <div class="container-blue">
        <div class="icon" v-for="(currentObject, indexObject) in objects">

            <img :src="currentObject.img" alt="">

            <p>
                {{ currentObject.name }}
            </p>



        </div>

    </div>
</template>

<style lang="scss">
.container-blue {
    border: 1px solid red;
    /* test */
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;

    display: flex;
    justify-content: space-evenly;
    align-items: center;

    color: white;

    

    .icon {
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 20px;
        
        img{
            width: 50px;
        }

    }
}
</style>