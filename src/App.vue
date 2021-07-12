<template>
  <div id="app">
    <Sidenav/>
    <MyOffer/>
  </div>
</template>

<script>
import Sidenav from "./components/sideNav"
import MyOffer from "./components/myOffer"
export default {
  components:{
    Sidenav,
    MyOffer
  }
}
</script>

<style>
#app{
  display:flex;
  position:relative;
  left: 0;
  top:0;
  right:0;
  min-width: 100%;
  height: 100%;
  background: radial-gradient(47.39% 118.47% at 3.68% -21.35%, rgba(255, 219, 19, 0.1) 0%, rgba(255, 125, 75, 0.1) 30.4%, rgba(231, 130, 247, 0.1) 62.15%, rgba(216, 65, 137, 0.1) 100%);
}
@media(max-width:500px){
  #app{
    position: absolute;
    overflow-x: hidden;
  }
}
</style>
