<template>
  <router-view/>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data () {
    return {
      //
    }
  }
}
</script>
<style>
.login-wraper {
  box-sizing: border-box;
  border-radius: 5px;
  min-height: 35vh;
  height: 40vh;
  box-shadow: 10px 10px 5px #777;
  width: 30vw;
  text-align: center;
  margin: 0 auto;
  transform: translateY(calc(50%));
  padding: 5px 40px;
  border: 1px solid #aaa;
}
body {
  width: 100vw;
  height: 100vh;
  padding: 0;
  margin: 0;
}
</style>
