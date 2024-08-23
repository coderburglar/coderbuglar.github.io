# 插件

> vite 只是给我们提供了一个基本的架子，但是我们可以使用填充这个框架

## 插件推荐

- @vitejs/plugin-legacy ： 为打包后的文件提供传统浏览器兼容性支持 (官方插件)
- vite-plugin-env-compatible ： 类似于 dotenv 但是这个地方把他添加到 import.meta.env 但是这个地方也可以自己写一个去做。
- vite-plugin-compression : 用于生成压缩文件。（比如 gzip 和 brotli)
- vite-plugin-optimizer : 帮助减少不必要的代码
- vite-plugin-imagemin： 图片压缩

![example]('../../../../../images/vite插件示例.png')
