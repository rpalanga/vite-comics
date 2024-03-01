<script>
import AppJumbotron from './AppJumbotron.vue';

export default{
    name: "AppNav",

    components: {
        AppJumbotron
    },

    data(){
        return {
            links: ["CHARATERS","COMICS","MOVIES","TV","GAMES","COLLECTIBLES","VIDEOS","FANS","NEWS","SHOP"],

            elemetIndex:0,

        }
    }
}

</script>

<template>

    <div class="container-nav">
        <div class="Navbar">
            <div class="logo-container">
                <img src="../../public/img/dc-logo.png" alt="">
            </div>
            <div>
                <ul>
                    <li v-for="(link, index) in links" :class="index == elemetIndex ? `active` : ``" >
                        {{ link }}
                    </li>
                    
                </ul>
            </div>
    
        </div>
        
    </div>

    <AppJumbotron></AppJumbotron>


  
 
</template>

<style lang="scss">

.container-nav{
    width: 100%;
  
  margin-left: auto;
  margin-right: auto;

  background-color: white;

}


.Navbar{
    
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;

    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px;

    .logo-container{
        display: flex;
        align-items: center;

        img{
            width: 80px;
        }
    }

    ul{
        list-style: none;

        display: flex;
        gap: 10px 20px;
        

        li{
            font-size: 20px;
            cursor: pointer;

            &.active{
                color: #3880F1;
            }
        }
    }
    

}

</style>
