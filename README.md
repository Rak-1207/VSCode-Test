# 写在前面

由于最近公司业务不是很忙，空闲时间比较多，于是就在纠结 Vue.js（之前就学习过）和 Node.js 先专研哪个比较好，最终选择了先玩玩 Node.js。经过一段时间的学习，就有了教程 [Node+Koa2+Mysql 搭建简易博客](http://www.wclimb.site/2017/07/12/Node-Koa2-Mysql-%E6%90%AD%E5%BB%BA%E7%AE%80%E6%98%93%E5%8D%9A%E5%AE%A2/) [GitHub 地址](https://github.com/wclimb/Koa2-blog)，想要了解的可以先看看，个人水平有限，希望可以帮到你。大概过来一个多月，我决定两路开工。使用 Node.js 给前端写接口，配备后台管理功能，先把后台搭建好。大概几天过后，后台一些简单的功能实现后，就开始用 Vue.js 开始搭建前台，也一直在想做点什么比较好，于是就做了个豆瓣评分类似的项目。

## 目录结构

```
|-- build                            // webpack配置文件
|-- config                           // 项目打包路径
|-- src                              // 源码目录
|   |-- assets                       // 图片文件
|   |-- base                   		 // 移动端适配
|   |-- components                   // 组件
|   |-- data                         // 接口
|   |-- router						 // 路由配置
|   |-- store                        // 状态管理
|   |-- style                        // 样式
|    	App.vue                      // 页面入口文件
|    	main.js                      // 程序入口文件
|-- static                           // 静态资源
|-- .babelrc                         // ES6语法编译配置
|-- .editorconfig                    // 代码编写规格
|-- .gitignore                       // git忽略的文件
|-- .postcssrc.js                    // post-loader的插件配置文件
|-- index.html                       // 入口html文件
|-- package.json                     // 项目及工具的依赖配置文件
```
