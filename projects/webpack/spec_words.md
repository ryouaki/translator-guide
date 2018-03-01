# 规范词汇表


### 中文仓库地址
https://github.com/webpack-china/webpack.js.org


### 统一固定词汇
- learn more! => 了解更多！
- see also => 参考
- details => 详细
- options => 选项
- Example => 示例
- default => 默认值
- see => 查看
- check out => 查看
- usage => 用法
- i.e/IE => 即；换句话
- up to => 取决于
- fallback => 备用
- hacks => 变通方案
- Links/References => 参考链接
- takeaway => 卖点/优势
- expensive => 高性能开销
- cheap => 低性能开销
- overhead => 间接开销/额外开销


### 不需要翻译的关键术语

- entry => 入口/输入
- entry points => 入口起点/输入起点
- output => 输出
- bundle => vt.打包（动词是打包的意思）n.bundle（名词不翻译）
- emitted => 生成/输出（原意为排出，类似管道输出，这里指的是生成或输出）
- emit => 同上
- resolve => resolve/解析
- long-term vendor-caching => 长效缓存
- Hot Module Replacement/HMR => 模块热替换
- on-demand loaded => 按需加载
- line to line mapping => 行到行映射 & generated source => 生成资源 & original source => 原始资源
示例：
Enables line to line mapping for all or some modules. This produces a simple source map where each line of the generated source is mapped to the same line of the original source.
对所有或某些模块启用「行到行映射(line to line mapping)」。这将生成基本的资源映射，即生成资源的每一行，映射到原始资源的同一行。
- template string => 模板字符串
- fine-grained => 细粒度
- granular => 粒度化


### 需要翻译的关键术语
- bundle => n.bundle/包文件/包（名词有捆绑、包裹的意思，是指将所有的依赖模块整合在一起，最终生成一个 js 文件）
- chunk => chunk/分块/块/模块（意思是把整体“拆分”或“分割”为块状）
- compiler => 解析器
- loader => 加载器
- runtime => webpack 运行时
- vendor => 第三方库，原意为供应商，指的应该是可提供全局对象 window.xxx 的固定 js 文件。
- library => 导出的库文件，详细说明：[代码分割 - Libraries](https://doc.webpack-china.org/guides/code-splitting-libraries) 和 [Authoring Libraries](https://doc.webpack-china.org/guides/author-libraries/) 这里有 [vendor、library 、externals 的区别](http://div.io/topic/1827)
- tree-shaking => [如何评价 Webpack 2 新引入的 Tree-shaking 代码优化技术？](https://www.zhihu.com/question/41922432)
- request => 指在 require() 语句中的表达式，如 require('./template/" + name + ".ejs') 中，request 就是 './template/" + name + ".ejs'。[Dependency Management](https://webpack.js.org/guides/dependency-management/) [管理依赖](https://doc.webpack-china.org/guides/dependency-management/) [Dependency Management校对](https://github.com/webpack-china/webpack.js.org/pull/184)

其他：
- understand => 识别。例句：The `webpack` compiler can understand modules written as ES2015 modules, CommonJS or AMD. => `webpack` 编译器(compiler)能够识别遵循 ES2015 模块语法、CommonJS 或 AMD 规范编写的模块。
- encapsulation => 封装
- well contained => 良好的封闭性
- self-contained => adj. 自成体系，独立的，自成一体的。不要译为自包含的。
