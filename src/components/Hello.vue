<template>
  <div class="hello">
    <div class="content">
      <div>
        <img src="../assets/logo.png">
        <h1 class="content-head is-center">{{ msg }}</h1>
      </div>
      <h2 class="content-subhead">Essential Links</h2>
      <div class="pure-menu pure-menu-horizontal">
        <ul class="pure-menu-list">
          <li class="pure-menu-item"><a class="pure-menu-link" href="https://vuejs.org" target="_blank">Core Docs</a></li>
          <li class="pure-menu-item"><a class="pure-menu-link" href="https://forum.vuejs.org" target="_blank">Forum</a></li>
          <li class="pure-menu-item"><a class="pure-menu-link" href="https://gitter.im/vuejs/vue" target="_blank">Gitter Chat</a></li>
          <li class="pure-menu-item"><a class="pure-menu-link" href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
          <br>
          <li class="pure-menu-item"><a class="pure-menu-link" href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
        </ul>
        <h2 class="content-subhead">Ecosystem</h2>
        <ul>
          <li class="pure-menu-item"><a class="pure-menu-link" href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
          <li class="pure-menu-item"><a class="pure-menu-link" href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
          <li class="pure-menu-item"><a class="pure-menu-link" href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
          <li class="pure-menu-item"><a class="pure-menu-link" href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
