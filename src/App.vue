<template>
  <div id="app">
    <!-- <div id="app_a">
    <div id="nav">
      <div id="router"><router-link to="/">Home</router-link> </div>
      <div id="router"><router-link to="/about">About</router-link> </div>
      <div id="router"><router-link to="/info">Info</router-link></div>
    </div>
    </div> -->
    <!-- <div class="content"> -->
      <router-view/>
    <!-- </div> -->
    <abc></abc>
  </div>
</template>

<script>
import center from './components/center/center';
export default {
  name:'app',

    data(){
      return{

      };
       
    },
    components:{
        'abc':center
    }
    
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0;
  margin: 0;


}

/* .content{
  height: 660px;
  background: #42b983;
} */
</style>
