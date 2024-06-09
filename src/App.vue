<script>
import HelloWorld from './components/HelloWorld.vue';
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default{
  components:{
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <body>
    <main>
      <div class="appTitle">
        <AppTitle />
      </div>
      <div class="img1">
        <AppHero />
      </div>
      
    </main>
  </body>
    
  
  
</template>

<style scoped>

</style>
