<script lang="ts" setup>
// 页脚需要的链接
const links = {
    Vue: "https://cn.vuejs.org/",
    Vite: "https://cn.vitejs.dev/",
    ElementPlus: "https://element-plus.org/zh-CN/",
}
</script>

<template>
  
  <div class="bg">
    <el-row justify="center">
      <p class="footer">
        Built with
        <a :href="links.Vue">Vue</a>,
        <a :href="links.Vite">Vite</a>, and
        <a :href="links.ElementPlus">Element Plus</a>.
      </p>
    </el-row>
  </div>
</template>

<style scoped>

/* 页脚背景 */
.bg {
  background-color: rgb(235, 235, 235);
}

/* 页脚文字 */
.footer {
  text-align: center;
  margin: 20px;
  z-index: 1;
}

</style>
