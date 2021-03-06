## Intro

一个具备主流项目基础配置、预留配置空间的 vue-typescript 模版，基于  vue 2.x + vue-cli 3 实现。

愿景是不再为新项目而重复性的初始化配置，诚恳欢迎 star 和 PR～ (´▽｀)

基于此模版的 vue-cli 3 插件请参见 [vue-cli-plugin-template](https://github.com/zoux/vue-cli-plugin-template)。

原始模版和思想来自于 [vue-develop-template](https://github.com/PerseveranceZ/vue-develop-template)。


## Use

```
npm i
npm run serve
npm run build
npm run lint
```


## Feature

- 基于 vue-cli 3
- 约定性的项目结构
- 集中管理的项目配置
- webpack require.context 实现 commonComponents router vuex 的自动注入
- 预留了 router axios 全局拦截器
- 开发环境默认启用 vuex 的严格模式、日志监控
- 可配置全局注入或按需加载 $axios $api $constants $utils 等服务
- 全局注入 scss-bem


## Framework

```
.
├── assets                              公共资源
│   ├── iconfont                        阿里 iconfont
│   ├── image
│   └── style
├── components                          公共组件
├── config                              项目配置
│   ├── interceptors                    拦截器配置
├── plugins                             插件配置
├── routes                              公共路由
├── service                             公共服务
│   ├── api                             ajax 请求模块
│   ├── constants                       constants 常量模块
│   ├── store                           vuex 状态模块
│   └── utils                           工具库
├── views                               模块/页面
├── App.vue                             根页面
├── main                                根实例
.
```


## License

MIT
