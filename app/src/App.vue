<template>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.citylist {
  margin: 0;
  padding: 0;
  background: #f5f5f5;
  font-size: 14px;
  .cityp {
    background: #ebebeb;
    text-indent: 10%;
    height: 30px;
  }
  .citydiv {
    padding-left: 15px;
    height: 45px;
    line-height: 45px;
    width: 90%;
    margin: auto;
    border-bottom: 1px rgb(184, 183, 183) solid;
  }
}
</style>
