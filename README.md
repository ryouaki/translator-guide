# 翻译人员参与指南

## [印记中文(docschina.org)](https://docschina.org)

介绍：
[印记中文(docschina.org)](https://docschina.org)是一个中文文档翻译生态圈，背后隐含着的是，我们致力于互联网技术中文文档翻译的基本理念和实际行动。


## FAQ
* 关注我们
  - Q: 我该如何关注印记中文公众号？
  - A: 扫描 [加入群聊](https://docschina.org/home/about) 中的二维码，或者直接添加公众号（印记中文翻译）。
  - Q: 我该如何加入印记中文文档翻译群（微信）？
  - A: 进去，或添加微信好友 李志华(@275091674) 进群。
  - Q: 我该如何加入印记中文文档翻译群（QQ）？
  - A: 扫描 [加入群聊](https://docschina.org/home/about) 中的二维码，或直接通过 QQ 群号（翻译 1 群 492361223 / 翻译 2 群 606946737）进入。
* 开始翻译
  - Q: 我想要翻译已有项目
  - A: 进入下面已有项目的仓库，寻找对应的翻译负责人，按照翻译流程就可以加入。
  - Q: 我想重新开始一个新的项目
  - A: 我们会评估项目，如果可行的话，我们会提供翻译流程、分支管理、打包部署等方面的支持。


### 合作
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/lcxfs1991.png?size=90) 李成熙 | [@lcxfs1991](https://github.com/lcxfs1991) | lcxfs1991@gmail.com | 249806703 | -

## 翻译指引

[gitlab 或 github 下 fork 后如何同步源的新更新内容？](https://www.zhihu.com/question/28676261/answer/44606041)

翻译指引目前还以 [webpack-china/webpack.js.org](https://github.com/webpack-china/webpack.js.org/) 的翻译方式为基础，大家优先参考 [webpack 2 翻译任务认领说明 - 入口目录](https://github.com/webpack-china/webpack.js.org/issues/17) 来认领文档翻译。后续会将指引编辑成文，放在本仓库当中。

## 分支管理

- 合并分支：http://mp.weixin.qq.com/s/_ricIlWhDbRZW-CmH0Ik5w
- 翻译流程：https://github.com/webpack-china/webpack.js.org
- git 命令示意图：![git 命令示意图](https://camo.githubusercontent.com/6f9cc78d28f03cf60b148d368cf89160c807c08c/687474703a2f2f7030773575717736622e626b742e636c6f7564646e2e636f6d2f696d6167652f706e672f7765627061636b2545372542462542422545382541462539312545362542352538312545372541382538422545352539422542452e706e67)

- 中文文案排版指北：https://github.com/mzlogin/chinese-copywriting-guidelines

通过 https://github.com/vinta/pangu.js 这个工具，可以很方便的自动添加空格，创建出符合「中文文案排版指北」的排版规则。

```
// 这是一段通过 Node.js 调用 pangu.js 来自动添加空格的代码，input.md 是源文件，output.md 是输出文件。
const fs = require('fs')

const pangu = require('pangu')
const data = pangu.spacingFileSync('./input.md')

fs.writeFile('output.md', data, (err) => {
  if (err) throw err;
  console.log('The file has been saved!');
})
```

## 项目总览

先选择你喜欢的翻译项目，我们目前提供了以下的选择。如果有其它你感兴趣的翻译，可以通过群组，或者 Github Issue 提出你的建议。

* 语言类
  - [Node.js](#nodejs)
  - [ECMAScript](#ecmascript)

* 前端框架类
  - [React](#react)
  - [Vue](#vue)
  - [Preact](#preact)

* 工程类
  - [webpack](#webpack)
  - [Rollup](#rollup)
  - [Babel](#babel)
  - [Parcel](#parcel)


### webpack
#### 项目情况
* webpack 2 中文文档翻译，由 李成熙 于 2017.01 发起和组织
* [webpack-china 中文文档](https://doc.webpack-china.org)
* [webpack-china 中文仓库](https://github.com/webpack-china/webpack.js.org)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/dear-lizhihua.png?size=90)<br>李志华 | [@dear-lizhihua](https://github.com/dear-lizhihua) | 275091674@qq.com | 275091674 | 275091674
![](https://github.com/lcxfs1991.png?size=90)<br>李成熙 | [@lcxfs1991](https://github.com/lcxfs1991) | - | - | -
![](https://github.com/Aladdin-ADD.png?size=90)<br>薛定谔的猫 | [@Aladdin-ADD](https://github.com/Aladdin-ADD) | - | - | -


### React
* React 中文文档目前由 余博伦([@discountry](https://github.com/discountry)) 在 [React docs in Chinese](https://github.com/discountry/react) 发起组织翻译，目前已经持续翻译跟进到 `v15.6.1` 版本的官方文档，文档已完整翻译，可能仍有少数错误需要修改。
* 愿意帮忙校对翻译的同学可以根据 [纠错指引](https://github.com/discountry/react/blob/master/README.md) 直接提交pr修改。
* 在 React@16 新版本发布之后，如果文档有较大的变动，可以按照 [React 中文文档翻译指南](https://github.com/discountry/react/tree/master/docs) 认领翻译新发布的内容。
* React 官方也发布了初步的翻译贡献流程，我们会先行整合之前翻译好的内容，积极的同学也可以直接在 [crowdin](https://crowdin.com/project/react) 网站上参与贡献翻译。

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/discountry.png?size=90)<br>余博伦 | [@discountry](https://github.com/discountry) | - | - | -


### babel
* [babel 中文文档](https://babeljs.cn/)
* [babel 文档翻译仓库](https://github.com/docschina/babeljs.io)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/QC-L.png?size=90)<br>李其昌 | [@QC-L](https://github.com/QC-L) | - | - | -


### parcel
* [parcel 中文文档](https://www.parceljs.io)
* [parcel 中文文档 - 备用链接](https://parceljs.docschina.org/)
* [parcel 文档翻译仓库](https://github.com/docschina/parceljs.io)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/QC-L.png?size=90)<br>李其昌 | [@QC-L](https://github.com/QC-L) | - | - | -


### Rollup
* [rollup 中文文档](https://rollupjs.cn/)
* [rollup 文档翻译仓库](https://github.com/docschina/rollupjs.org)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/lcxfs1991.png?size=90)<br>李成熙 | [@lcxfs1991](https://github.com/lcxfs1991) | - | - | -


### Vue
#### 项目情况
* vuefe 是由 丁一鸣(@dingyiming) 于 2016.08 在 [vuefe 中文仓库(vuefe/vuejs.org)](https://github.com/vuefe/vuejs.org)发起和组织的 Vue.js 2.x 中文文档翻译，于 2016.10 结束翻译后，合并至[官方仓库(vuejs/cn.vuejs.org)](https://github.com/vuejs/cn.vuejs.org)。
* 其后，两个仓库并行存在，中文仓库由 Vue 中文社区维护，而 vuefe 仓库也在一直维护。
* vuefe 目前重点，旨在提供优质的审校，具体我们的工作成果，可以查看最近几个月的 [pull-request](https://github.com/vuefe/vuejs.org/pulls)。
* [vuefe 中文文档](https://vuefe.cn/v2/guide/)
* [vuefe 中文仓库](https://github.com/docschina/vuejs.org)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/dear-lizhihua.png?size=90)<br>李志华 | [@dear-lizhihua](https://github.com/dear-lizhihua) | 275091674@qq.com | 275091674 | 275091674


### Node.js
* [Node.js 中文文档](http://nodejs.cn/)
* [Node.js 文档翻译仓库](https://github.com/nodejscn/node-api-cn)
* [正在招募模块负责人，快来应征啦！](https://github.com/nodejscn/node-api-cn#加入我们)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/h7lin.png?size=90)<br>h7lin | [@h7lin](https://github.com/h7lin) | - | - | -


### RxJS
* [RxJS 5 中文文档](http://cn.rx.js.org/)
* [RxJS 5 中文文档 - 翻译仓库](https://github.com/RxJS-CN/RxJS-Docs-CN)
* [RxJS 5 基本原理](https://rxjs-cn.github.io/rxjs5-ultimate-cn/)
* [RxJS 5 基本原理 - 翻译仓库](https://github.com/RxJS-CN/rxjs5-ultimate-cn)
* [学习 RxJS](https://rxjs-cn.github.io/learn-rxjs-operators/)
* [学习 RxJS - 翻译仓库](https://github.com/RxJS-CN/learn-rxjs-operators)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/SangKa.png?size=90)<br>SangKa | [@SangKa](https://github.com/SangKa) | - | - | -


### ECMAScript
* [ECMAScript 中文文档](https://ecma262.docschina.org/)
* [ECMAScript 文档翻译仓库](https://github.com/docschina/ecma262)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/realywithoutname.png?size=90)<br>realywithoutname | [@realywithoutname](https://github.com/realywithoutname) | - | - | -


### Koa
* [Koa 中文文档](https://koajs.cn/)
* [Koa 中文文档 - 备用链接](https://koajs.docschina.org/)
* [Koa 文档翻译仓库](https://github.com/demopark/koa-docs-Zh-CN)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/demopark.png?size=90)<br>demopark | [@demopark](https://github.com/demopark) | - | - | -


### Preact
* [praect 中文文档](https://preactjs.com/) ，在网站底部选择语言
* [preact 文档翻译仓库](https://github.com/docschina/preact-www)

#### 项目维护
负责人 | GitHub | mail | QQ | weixin
--- | --- | --- | --- | ---
![](https://github.com/lcxfs1991.png?size=90)<br>李成熙 | [@lcxfs1991](https://github.com/lcxfs1991) | - | - | -


## 特别感谢

在此非常感谢 [腾讯云](https://cloud.tencent.com/) 和 [AlloyTeam](http://alloyteam.com/) 在背后的支持和贡献


## 授权方式

[印记中文](https://docschina.org)翻译的所有文档，遵循[“保留署名—非商用”创意共享 4.0 许可证（CC BY-NC 4.0）](https://creativecommons.org/licenses/by-nc/4.0/deed.zh)授权方式，你不用知会我们就可以转载，但必须保持署名（特别是：链接到 https://docschina.org 或印记中文相应的网站，并且不得去掉本页入口链接，也不得修改本页内容），并且不得用于商业目的。如果需要进行任何商业推广，请接洽 印记中文负责人李成熙(@lcxfs1991)（QQ: 249806703 && 邮箱：lcxfs1991@gmail.com），我们将给出积极的回应。
