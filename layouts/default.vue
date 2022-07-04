<template>
  <div class="font-Montserrat">
   
   <Header></Header>
   
    <Nuxt />
     
  </div>
</template>

<script>
import Header from '@/components/header'
  export default {
     name:'defaulLayout',
      components: { Header},
  }
  </script>

<style>
 
</style>
