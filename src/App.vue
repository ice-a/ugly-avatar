<template>
  <FaceGenerator/>
  <div class="footer"><p><a href="http://qd.lideshan.top/my/" target="_blank">自动化签到</a></p>
    <p><a href="http://pan.lideshan.top/" target="_blank">木子的秘密</a></p>
    <p><a href="https://cook.lideshan.top/" target="_blank">一位大厨的崛起之路</a></p>
    <p><a href="https://tools.lideshan.top/" target="_blank">木子的工具箱</a></p>
    <p><a href="https://eat.lideshan.top/" target="_blank">不知道吃什么就去看看</a></p>
    <p><a href="https://remake.lideshan.top/public/index.html" target="_blank">重生之我在人间两万年</a></p>
    <p><a href="https://ip.lideshan.top/" target="_blank">木子的ip信息,爆破他</a></p>
    <p><a href="https://lideshan.top/" target="_blank">去访问有趣的木子</a></p>
    <p>Powered by Cloudflare Workers</p></div>
</template>

<script>
import FaceGenerator from './views/FaceGenerator.vue'

export default {
  components: {FaceGenerator},
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;

  .footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
  }
}
</style>
