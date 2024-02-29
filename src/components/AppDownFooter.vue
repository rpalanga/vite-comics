<script>
export default{
    name: "AppDownFooter",


   
}

</script>

<template>

    <div class="AppDownFooter-container">
       
        <div class="footer-left">

            <button>
                SIGN-UP NOW!
            </button>

        </div>
        <div class="footer-right">
            <span>FOLLOW US</span>
            <img src="../../public/img/footer-facebook.png" alt="">
            <img src="../../public/img/footer-twitter" alt="">
            <img src="../../public/img/footer-youtube.png" alt="">
            <img src="../../public/img/footer-pinterest.png" alt="">
            <img src="../../public/img/footer-periscope.png" alt="">

            
        </div>

    </div>

  
 
</template>

<style lang="scss">




.AppDownFooter-container{
    border: 1px solid red;
    /* test */
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
    padding: 30px;

    display: flex;
    justify-content: space-between;
    align-items: center;

    .footer-left{


        button{
            color: white;
            background-color: #242424;
            padding: 18px 14px;
            border-color:#3880F1 ;

        }
    }




    .footer-right{
        display: flex;
        align-items: center;
        gap: 10px;


        span{
            margin-right: 10px;
            color: #3880F1;
    
            font-size: 16px;
            font-weight: bold;
        }
    }

   
    

}

</style>