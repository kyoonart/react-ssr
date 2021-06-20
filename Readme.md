React 服务端渲染，使用方式：

1、到 node_server 文件夹下，执行 npm install，然后执行 node app.js，启动后端接口的服务器(端口为 4000，用其他语言实现均可)

2、npm install nodemon npm-run-all -g 全局安装 nodemon 工具和 npm-run-all，不然之后的项目命令会无法识别

3、到 my_ssr 文件夹下，执行 npm install, 然后执行 npm run dev 启动项目(命令配置细节请看 package.json 里面的 script 内容),打开浏览器通过 localhost:3001 即可访问。

配套技术点详解文章地址:
https://juejin.im/post/5d1fe6be51882579db031a6d
跟着教程走了一遍 ssr
