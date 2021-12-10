# 搭建服务器需要的一些 JS 文件

大家随意调用！

```js
// 首先是页面樱花效果的 JS 代码
<script src="https://cdn.jsdelivr.net/gh/2019wanan/vovz@1.0/sakura.js"></script>

// 鼠标点击页面，出现彩色气球爆炸效果	两个都要引入
// 这里用的是 猫云CDN .你可以选择其他种，但是anime的版本必须是2.2.0。3.2版本有点不适配
<canvas
    class="fireworks"
    style="position: fixed; left: 0; top: 0; z-index: 1; pointer-events: none"
></canvas>
<script src="https://cdn.bootcdn.net/ajax/libs/animejs/2.2.0/anime.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/2019wanan/vovz@1.0/clickBom.js"></script>
```
