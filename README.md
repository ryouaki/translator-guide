# translator-guide
翻译人员参与指南

## [印记中文(docschina.org)](https://docschina.org)

介绍：
[印记中文(docschina.org)](https://docschina.org)是一个技术文档导航站点（暂时只有前端，未来可能拓展），背后隐含着的是，我们致力于互联网技术中文文档翻译的基本理念和实际行动。

* 我该如何关注印记中文公众号？扫描 [docschina.org/group](https://docschina.org/group) 中的二维码，添加公众号
* 我该如何加入印记中文文档翻译群（微信）？扫描 [docschina.org/group](https://docschina.org/group) 中的二维码进去，或添加微信好友李志華(@275091674)进群
* 我该如何加入印记中文文档翻译群（QQ）？docschina翻译1群 492361223 & docschina翻译2群 606946737


## 项目总览

先选择你喜欢的翻译项目，我们目前提供了以下的选择。如果有其它你感兴趣的翻译，可以通过群组，或者 Github Issue 提出你的建议。

* 语言类
  - [nodejs](#nodejs)

* 前端框架类
  - [react](#react)
  - [vue](#vue)
  - [preact](#preact)

* 工程类
  - [webpack](#webpack)
  - [rollup](#rollup)
  - [babel](#babel)
  - [parcel](#parcel)


### webpack

介绍：
* webpack-china 是由 李成熙([@lcxfs1991](https://github.com/lcxfs1991)) 于 2017.01 在 [webpack-china 中文仓库(webpack-china/webpack.js.org)](https://github.com/webpack-china/webpack.js.org)发起和组织的 webpack 2.x 中文文档翻译，由于 webpack 文档较多，官方改动较大，至今仍然处于翻译中。
* [webpack-china 中文文档 - 网站链接](https://doc.webpack-china.org)
* [webpack-china 中文仓库](https://github.com/webpack-china/webpack.js.org)
* [webpack-china wiki](https://github.com/webpack-china/webpack.js.org/wiki)

### Rollup
* [rollup 中文文档 - 网站链接](https://rollupjs.org/zh)
* [rollup 文档翻译仓库](https://github.com/rollup-china)

### babel
* [babel 中文文档 - 网站链接](https://babeljs.cn/)
* [babel 文档翻译仓库](https://github.com/docschina/babeljs.io)

### parcel
* [parcel 中文文档 - 网站链接](https://www.parceljs.io)
* [parcel 中文文档 - 备用链接](https://parceljs.docschina.org/)
* [parcel 文档翻译仓库](https://github.com/docschina/parceljs.io)

### React

* React 中文文档目前由 余博伦([@discountry](https://github.com/discountry)) 在 [React docs in Chinese](https://github.com/discountry/react) 发起组织翻译，目前已经持续翻译跟进到 `v15.6.1` 版本的官方文档，文档已完整翻译，可能仍有少数错误需要修改。
* 愿意帮忙校对翻译的同学可以根据 [纠错指引](https://github.com/discountry/react/blob/master/README.md) 直接提交pr修改。
* 在 React@16 新版本发布之后，如果文档有较大的变动，可以按照 [React 中文文档翻译指南](https://github.com/discountry/react/tree/master/docs) 认领翻译新发布的内容。
* React 官方也发布了初步的翻译贡献流程，我们会先行整合之前翻译好的内容，积极的同学也可以直接在 [crowdin](https://crowdin.com/project/react) 网站上参与贡献翻译。

### Preact
* [praect 中文文档 - 网站链接](https://preactjs.com/) ，在网站底部选择语言
* [preact 文档翻译仓库](https://github.com/docschina/preact-www)

### Vue

介绍：
* vuefe 是由 丁一鸣(@dingyiming) 于 2016.08 在 [vuefe 中文仓库(vuefe/vuejs.org)](https://github.com/vuefe/vuejs.org)发起和组织的 Vue.js 2.x 中文文档翻译，于 2016.10 结束翻译后，合并至[官方仓库(vuejs/cn.vuejs.org)](https://github.com/vuejs/cn.vuejs.org)。
* 其后，两个仓库并行存在，中文仓库由 Vue 中文社区维护，而 vuefe 仓库也在一直维护。
* vuefe 目前重点，旨在提供优质的审校，具体我们的工作成果，可以查看最近几个月的 [pull-request](https://github.com/vuefe/vuejs.org/pulls)。
* [vuefe 中文文档 - 网站链接](https://vuefe.cn/v2/guide/)
* [vuefe 中文仓库](https://github.com/vuefe/vuejs.org)
* [Vue wiki](https://github.com/vuefe/vuejs.org/wiki)

### nodejs
* [Node.js 中文文档 - 网站链接](http://nodejs.cn/) 
* [Node.js 文档翻译仓库](https://github.com/nodejscn/node-api-cn)
* [正在招募模块负责人，快来应征啦！](https://github.com/nodejscn/node-api-cn#加入我们)


## 翻译指引

[gitlab 或 github 下 fork 后如何同步源的新更新内容？](https://www.zhihu.com/question/28676261/answer/44606041)

翻译指引目前还以 [webpack-china/webpack.js.org](https://github.com/webpack-china/webpack.js.org/) 的翻译方式为基础，大家优先参考 [webpack 2 翻译任务认领说明 - 入口目录](https://github.com/webpack-china/webpack.js.org/issues/17) 来认领文档翻译。后续会将指引编辑成文，放在本仓库当中。

## 授权方式

[印记中文](https://docschina.org)翻译的所有文档，遵循“保留署名—非商用”创意共享 4.0 许可证（CC BY-NC 4.0）授权方式，你不用知会我们就可以转载，但必须保持署名（特别是：链接到 https://docschina.org 或印记中文相应的网站，并且不得去掉本页入口链接，也不得修改本页内容），并且不得用于商业目的。如果需要进行任何商业推广，请接洽 印记中文负责人李成熙(@lcxfs1991)（QQ: 249806703 && 邮箱：lcxfs1991@gmail.com），我们将给出积极的回应。

本文档首发于[印记中文(docschina.org)](https://docschina.org)。如果你要进行转载，请自行同步。
