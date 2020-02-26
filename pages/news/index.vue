<template>
  <div>
    <h2>这是news 页面</h2>
    <h3>传过来的参数{{$route.params.nuewsId}}</h3>
    <nuxt-link :to="{name: 'index'}">home</nuxt-link>
    <nuxt-link to="/news/123">news-1</nuxt-link>
    <nuxt-link :to="{name: 'news-id',params: {id: 123}}">news-1 第二种写法</nuxt-link>
    <a href="/news/456">News-2</a>
  </div>
</template>
<script>
export default {
  transition: 'test'
}
</script>