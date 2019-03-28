# 项目启动
+ 本地安装 [Yarn](https://yarn.bootcss.com/docs/getting-started/)
+ 安装依赖
```
yarn install
``` 
如果安装慢，全局修改镜像源
```
yarn config set registry https://registry.npm.taobao.org/
```
+ 本地启动
```
yarn dev
```
+ 构建静态文件
```
yarn build
```
默认情况下，文件将会被生成在 .vuepress/dist，也可以通过 .vuepress/config.js 中的 dest 字段来修改，生成的文件可以部署到任意的静态文件服务器上，参考[部署](https://vuepress.vuejs.org/zh/guide/deploy.html#github-pages)来了解更多。