<template>
  <MyHeader/>
  <router-view/>
  <MyFooter/>
</template>

<script>
import MyHeader from './components/includes/MyHeader.vue';
import MyFooter from './components/includes/MyFooter.vue';
export default{
  name:'app',
  components:{MyHeader,MyFooter},
  
  
}
</script>

<style scoped>
</style>
