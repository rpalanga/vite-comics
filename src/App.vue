<script>
import AppNav from './components/AppNav.vue';
import AppComics from './components/AppComics.vue';
import AppFooter from './components/AppFooter.vue';
import AppDownFooter from './components/AppDownFooter.vue';

export default {
  components: {
    AppNav,
    AppComics,
    AppFooter,
    AppDownFooter
  }
}

</script>

<template>

  <div class="container">
    <div class="header">
      <AppNav></AppNav>

    </div>

 
    <div class="up-main">
      <AppComics></AppComics>

    </div>
    
    <div class="up-footer">
      <AppFooter></AppFooter>

    </div>
    <div class="down-footer">
      <AppDownFooter></AppDownFooter>
    </div>


  </div>



</template>

<style lang="scss">
@use "./styles/newstyle" as *;


.container{
  


  


}


</style>
