<template>  
    <div id="app">
      <img src="./assets/logo.png" />
        <router-view>
        </router-view>  
    </div>
</template>
<script>
import UIkit from 'uikit';
import Icons from 'uikit/dist/js/uikit-icons';
UIkit.use(Icons);
export default {  
    name: 'app',
};
</script>
<style lang="less">
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
