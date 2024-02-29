<script>
export default{
    name: "AppFooter",

    data(){
        return{
            listOne:["Characters","Comics","Movies","TV","Games","Videos","News"],
            listTwo:["Shop DC","Shop DC Collectibles"],
            listThree:["Characters","Comics","Movies","TV","Games","Videos","News"],
            listFour:["Characters","Comics","Movies","TV","Games","Videos","News"],
                
        }
    }
}

</script>

<template>

    <div class="footer-container">

        <div class="links">

            <div id="link-col">
                <h3>DC COMICS</h3>
                <ul v-for="listElement in listOne">
                    <li> {{ listElement }}</li>
                   
                </ul>
                <h3>SHOP</h3>
                <ul v-for="listElement in listTwo">
                    <li>{{ listElement }}</li>
                    
                </ul>
            </div>
            <div id="link-col-1">
                <h3>DC</h3>
                <ul  v-for="listElement in listThree">
                    <li> {{ listElement }}</li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul>
    
            </div>
    
            <div id="link-col-2">
                <h3>SITES</h3>
                <ul  v-for="listElement in listFour">
                    <li>{{ listElement }}</li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul>
    
            </div>
        </div>

        <img src="../../public/img/dc-logo-bg.png" alt="">







    </div>


  
 
</template>

<style lang="scss">

.footer-container{
    border: 1px solid red;
    /* test */
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;

    display: flex;
   
    align-items: center;

    color: white;

    position: relative;
    overflow: hidden;

    img{
        position: absolute;
        right: 50px;
        width: 35%;
    }

    .links{
        display: flex;
        padding-top: 30px;
        padding-bottom: 30px;
    }

    ul{
        list-style: none;

        li{
            font-weight: lighter;
            font-size: small;
        }

    }


    #link-col{
        display: flex;
        flex-direction: column;
    }
    #link-col-1{
        padding: 10px;
    }
    #link-col-2{
        padding: 10px;
    }


}

</style>