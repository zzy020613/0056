<template>
  <div id="app" class="">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "app",
};
</script>

<style lang="scss">
*{
  padding: 0;
  margin:0;
}
html,body{
  width: 100%;
  height: 100%;
  //margin: 0;
  //padding: 0;
}
#app{
  width: 100%;
  height:100%;
}

router-view{
  width: 100%;
  height:100%;
}
body {
  padding: 0;
  margin: 0;
}
</style>
