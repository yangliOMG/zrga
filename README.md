# react + react-router + redux + webpack
* redux 拆分为：redux + redux-thunk

> redux-thunk可升级为redux-saga
从redux-thunk到redux-saga实践：[https://segmentfault.com/a/1190000009928167]
```
相比Redux Thunk，使用Redux Saga有几处明显的变化：

在组件中，不再dispatch(action creator)，而是dispatch(pure action)
组件中不再关注由谁来处理当前action，action经由root saga分发
具体业务处理方法中，通过提供的call/put等帮助方法，声明式的进行方法调用
使用ES6 Generator语法，简化异步代码语法
```


# antd-pro: react + dva + roadhog
* dva：redux + redux-saga + react-router  (基于 redux、redux-saga 和 react-router 的轻量级前端框架)
dva-github：[https://github.com/dvajs/dva/blob/master/README_zh-CN.md]
dva文档：[https://dvajs.com/guide/]
* roadhog：webpack  (基于 webpack 的封装工具，目的是简化 webpack 的配置)
roadhog-github：[https://github.com/sorrycc/roadhog/blob/master/README_zh-cn.md]


# antd-pro2: react + dva + umi
* umi：roadhog + 路由  (类似 next.js/nuxt.js，辅以一套插件机制，目的是通过框架的方式简化 React 开发)
umi文档：[https://umijs.org/zh/guide/]
用Next.js快速上手React服务器渲染：[https://segmentfault.com/p/1210000010368182/read]
