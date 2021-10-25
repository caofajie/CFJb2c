<template>
  <nav>顶部导航栏</nav>
  <header>头部组件</header>
  <div class="main">
  <!-- 二级路由 -->
  <router-view />
  </div>
  <footer>底部组件</footer>
</template>
<script>
export default {
  name: 'Layout'
}
</script>
