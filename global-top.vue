<!-- https://sli.dev/custom/global-layers.html#example -->
<template>
  <!-- https://v3.cn.vuejs.org/guide/class-and-style.html#%E7%BB%91%E5%AE%9A%E5%86%85%E8%81%94%E6%A0%B7%E5%BC%8F -->
  <footer :style="$slidev.nav.currentPage === 1 ? { color: 'white' } : {}"
          class="absolute bottom-0 right-0 p-7">
    {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
  </footer>
</template>
