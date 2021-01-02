<template>
  <div id="app">
   <Mobile/>
    <router-view/>
  </div>
</template>

<script>
import Mobile from  "./components/Mobile.vue";
export default {
  name: 'App',
  components:
   { 
     Mobile
   },
}
</script>

<style>

</style>
