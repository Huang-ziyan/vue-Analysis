# vue-Analysis

## 项目结构

- .circleci 自动集成 持续集成 持续部署工具的配置文件
- .github 项目的相关文档说明
- benchmarks 基准，性能测试文件 vue 的跑分 demo 比如大数据量的 table 或者渲染大量 SVG
- dist 构建后输出的不同版本 vue 文件 生产和开发包
- examples 部分示例 用 vue 写的一些小 demo
- flow 在 vue 项目中使用了 flow 进行静态类型检查
- packages 包含服务端渲染和模版编译器两种不同的 npm 包,是提供给不同使用场景使用的
- scripts 存放 npm 的配置文件
- src 核心内容
  - compiler 包含 vue.js 所有编译相关的代码
  - core vue 的核心代码 包括内置组件 全局 API 封装 vue 实例化 观察者 虚拟 DOM 工具函数
  - compentents 组件相关属性
  - global-api 全局 API
  - instance 实例化相关内容 生命周期 事件等
  - observer 响应式核心目录 双向数据绑定相关文件
  - util 工具方法
  - vdom 包含虚拟 DOM
    -platforms 和平台相关的内容
    -server 服务端渲染
    -sfc 转换单文件组件
    -shared 全局共享的方法和常量
- test 测试用例
- types ts 声明文件
- .babelrc.js babel 配置
- .editorconfig 文本编码样式配置文件
- .eslintignore eslint 忽略文件
- .eslintrc.js eslint 配置文件
- .flowconfig flow 配置文件
- .gitigoore 忽略文件
- .BACKERS.md 赞助信息文件
- LICENSE 项目开源协议
- package.json 依赖
- README.md 说明文件
- yarn.lock yarn 版本锁文件
