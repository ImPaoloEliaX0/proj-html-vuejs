<template>
  <div id="app">

    <MyHeader/>
    <MyMain/> 
    <MyFooter/>   
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyMain from './components/MyMain.vue';
import MyFooter from './components/MyFooter.vue';
export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter
    
  }
}
</script>

<style lang="scss">
/* REGOLE GENERALI */
ul{
    list-style: none;
}
a{
    text-decoration: none;
    text-transform: uppercase;
    color: #666665;
}
h1{
    color: #fff;
    text-transform: uppercase;
    font-size: 3em;
}
.btn{
    background-color: #f9d03f;
    font-size: 0.7em;
    letter-spacing: 1.1px;
}
</style>