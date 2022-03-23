## 田同学 - web 前端开发工程师

### 基本资料

个人信息：田同学 / 21 岁 / 杭州市临平区

联系方式：15211111111 / 12345678@qq.com

教育经历：计算机网络应用（2017.09-2021.05）

Github：https://github.com/Tyh2001

### 开源贡献

- 独立开发轻量级组件库 [tyh-ui](https://github.com/Tyh2001/tyh-ui)，基于 vue3 + TypeScript。内部共包含 30+ 常用组件。并带有详细的[官方文档](https://tianyuhao.cn/v3)。
- 独立开发 vscode 主题插件 [tyh-theme](https://github.com/Tyh2001/tyh-theme-vscode)。
- 常在 Github 活跃，发现优质项目，阅读源码。[blog](https://tianyuhao.cn/blog) 进行学习总结。[掘金](https://juejin.cn/user/2243446742456888)发布技术文章。

### 专业技能

- 熟练使用 ES6 和 vue 全家桶，了解 vue 周边生态
- 熟练各种 ui 组件库，擅长组件封装
- 熟悉后端开发逻辑，会定制数据结构
- 了解基础 http 网络协议和算法

### 工作经历

- 2021-05-10 ～ 2022-03-22 杭州xx电子商务有限公司 - 担任前端开发

### 项目经历

#### tyh-ui 组件库

`vue3` `vite` `TypeScript` `pnpm` `highlight.js`

- 带领两个小伙伴一起维护组件库日常开发
- 采用 monorepo + pnpm 构建，核心使用 vue3 + TypeScript 实现常用组件 `30+`
- 组件内部进行多代码优化、性能优化、样式优化、体积优化等
- 设计初期，组件内部设有大量变量和函数，多次性能优化和代码优化之后，减少大量冗余代码，并将函数进行封装，通过解构获取，并用 TypeScript 重构
- 样式优化加入了更细节的样式，比如按钮的 hover 状态、点击状态，都有明显的感知，提升用户体验
- 体积优化在多处细节上，采用`权衡的艺术`思想进行简化代码，将可抽离出来的函数全部抽离，代码能简化尽量简化，实现用最少代码实现相同功能
- 官网第一次性能优化，通过减少依赖将包的大小从**2.1MB**优化到了**823KB**
- 官网第二次优化通过将在线图片和压缩图片的方式，将包的大小从 **823KB**优化到了**472KB**
- 网站的性能评分 从 80 分 优化到 [98分](https://github.com/Tyh2001/tian-classmate/blob/master/assets/score-98.png?raw=true)
- 目前正在筹备开发全新组件库 [Spring-ui](https://github.com/Tyh2001/spring-ui)

#### 花旗银行投票项目

`vue3` `tyh-ui` `axios` `Echarts`

- 花旗银行需要拥有一个可以进行投票实时展示的平台，我负责开发一个投票系统帮助完成投票需求，并在短期内上线完成需求
- 每次交互都会给用户舒适的用户体验
- 基于 localStorage 和 vuex 缓存用户信息
- 独立封装工具函数、组件等
- 规定后端返回指定 json 数据结构
