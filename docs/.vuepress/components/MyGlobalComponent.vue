<template>
  <div v-html="htmlContent"></div>
</template>

<script>
export default {
  name: 'MyGlobalComponent',
  computed: {
    htmlContent() {
      return `
        <div>
          <a href="http://www.liyansheng.top/"><img src="https://img.shields.io/badge/👩‍💻木子-博客-00dfbf" alt="Space"></a>
          <img src="https://img.shields.io/badge/公众号-《编程亿点有趣》-brightgreen" alt="WeChat">
          <a href="https://yan-sheng-li.github.io/project/"><img src="https://img.shields.io/badge/👩‍💻木子-空间-blue" alt="Space"></a>
          <a href="https://blog.csdn.net/weixin_44107140"><img src="https://img.shields.io/badge/CSDN-博客-red" alt="CSDN"></a>
          <a href="https://gitee.com/yan-sheng-li"><img src="https://img.shields.io/badge/Gitee-码云-orange" alt="Gitee"></a>
          <a href="https://my.oschina.net/u/5021863"><img src="https://img.shields.io/badge/oschaina-开源中国-279c59" alt="oschaina"></a>
          <a href="https://qm.qq.com/cgi-bin/qm/qr?k=NZUoWMzd3PQLWwxRGMiBNYEnVkEdNq__&jump_from=webapi&authKey=kgAofDqUzgwMCSX+UQQwxf837zMeWFGGmo4iIcbgkklW2pdfmVOlxPWAK6sMYMaC"><img src="https://img.shields.io/badge/点我-Q作者：619298035-18a2ea" alt="QQ Group"></a>
        </div>
      `;
    }
  }
}
</script>
