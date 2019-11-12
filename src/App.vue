<template>
  <div id="app">
   <comment></comment>
  </div>
</template>

<script>
import Comment from './components/Comment.vue'

export default {
  name: 'app',
  components: {
    Comment
  }
}
</script>

<style>
#app {
  display: flex;
  justify-content: center;
  font-family: lucida grande, lucida sans unicode, lucida, helvetica,
    Hiragino Sans GB, Microsoft YaHei, WenQuanYi Micro Hei, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
