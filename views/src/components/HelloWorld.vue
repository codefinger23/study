<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      关于项目的一些快捷地址<br>
      <a href="https://cli.vuejs.org/zh/config/" target="_blank" rel="noopener">vue.config.js</a>  配置参考，修改后端代理可能需要.
    </p>
    <h3>Express相关的</h3>
    <ul>
      <li><a href="https://expressjs.com/zh-cn/" target="_blank" rel="noopener">Express Core</a></li>
    </ul>
    <h3>vuejs相关的</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Vue Core</a></li>
    </ul>
    <h3>相关组件</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
