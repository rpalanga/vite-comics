<script>
import AppNav from './components/AppNav.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppComics from './components/AppComics.vue';

export default {
  components: {
    AppNav,
    AppMain,
    AppComics,
    AppFooter
  }
}

</script>

<template>

  <div class="container">
    <div class="header">
      <AppNav></AppNav>

    </div>
    <div class="up-main">

    </div>

  </div>



</template>

<style lang="scss">
@use "./styles/newstyle" as *;

.container{
  border: 1px solid white;

  // test
  width: 100%;
  
  margin-left: auto;
  margin-right: auto;

  .header{
  background-color: white;

  }

}


</style>
