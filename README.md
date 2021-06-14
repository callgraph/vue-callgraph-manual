# vue-callgraph-manual

内核函数调用关系分析平台使用帮助

## 文档内容

基于node.js的源代码调用图分析工具使用文档，介绍页面模块使用方法。

## 查看连接

校内wiki：<http://os.cs.tsinghua.edu.cn/research/kernel/callgraph2017>

Gitbook文档：<https://callgraph.github.io/vue-callgraph-manual/>

## 路径对应章节

* ./README.md ……………………………… 介绍
* ./web/intr.md ……………………………… 页面模块
  * ./web/usage.md ……………………………… 使用说明
* ./callgraph/intr.md ……………………………… Call Graph模块
  * ./callgraph/summary.md ……………………………… 模块简介
  * ./callgraph/usage.md ……………………………… 使用说明
* ./functionlist/intr.md ……………………………… Function List模块
    * ./functionlist/summary.md ……………………………… 模块简介
    * ./functionlist/usage.md ……………………………… 使用说明
* ./question-answer/intr.md ……………………………… 常见问题

### 目录编辑

* ./SUMMARY.md ……………………………… 目录大纲

## 更新方式

更新路径对应的markdown文档，删除docs目录，重新打包，将_book目录重命名为docs，并push到git仓库中

## 打包发布相关命令

```sh
# 初始化gitbook
gitbook init

# 启动本地gitbook，可在http://localhost:4000 来查看gitbook运行效果
gitbook serve

# 打包生成gitbook的页面文件
gitbook build
# 打包后将_book目录重命名为docs

```