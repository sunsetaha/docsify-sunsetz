# Docsify
> 打造最快捷、最轻量级的个人&团队文档

## 前置准备
  - 环境：node.js
  - 工具：docsify-cli 
    ```node
      npm i docsify-cli -g 
    ```
## 搭建
### 初始化
  ```
    docsify init ./Docsify-Guide
  ```

  初始化成功后，可以看到 ./docs 目录下创建的几个文件

  index.html 入口文件

  README.md 会做为主页内容渲染

  .nojekyll 用于阻止 GitHub Pages 忽略掉下划线开头的文件

  直接编辑 docs/README.md 就能更新文档内容，当然也可以添加更多页面。

### 本地运行
  ```
    docsify serve ./Docsify-Guide   
  ```

### 部署
  [docker部署](https://developer.aliyun.com/article/1266542)


## 配置
  [看文档](https://docsify.js.org/#/)