# mall-admin-web

## 项目介绍

`mall-admin-web`是一个电商后台管理系统的前端项目，基于 Vue+Element 实现。主要包括商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等功能。

### 技术选型

| 技术              | 说明                    | 官网                                                                                               |
| ----------------- | ----------------------- | -------------------------------------------------------------------------------------------------- |
| Vue               | 前端框架                | [https://vuejs.org/](https://vuejs.org/)                                                           |
| Vue-router        | 路由框架                | [https://router.vuejs.org/](https://router.vuejs.org/)                                             |
| Vuex              | 全局状态管理框架        | [https://vuex.vuejs.org/](https://vuex.vuejs.org/)                                                 |
| Element           | 前端 UI 框架            | [https://element.eleme.io/](https://element.eleme.io/)                                             |
| Axios             | 前端 HTTP 框架          | [https://github.com/axios/axios](https://github.com/axios/axios)                                   |
| v-charts          | 基于 Echarts 的图表框架 | [https://v-charts.js.org/](https://v-charts.js.org/)                                               |
| Js-cookie         | cookie 管理工具         | [https://github.com/js-cookie/js-cookie](https://github.com/js-cookie/js-cookie)                   |
| nprogress         | 进度条控件              | [https://github.com/rstacruz/nprogress](https://github.com/rstacruz/nprogress)                     |
| vue-element-admin | 项目脚手架参考          | [https://github.com/PanJiaChen/vue-element-admin](https://github.com/PanJiaChen/vue-element-admin) |
| less              | 样式语法                | [https://lesscss.com/](https://lesscss.com/)                                                       |

### 项目布局

```lua
src -- 源码目录
├── api -- axios网络请求定义
├── assets -- 静态图片资源文件
├── components -- 通用组件封装
├── icons -- svg矢量图片文件
├── router -- vue-router路由配置
├── store -- vuex的状态管理
├── styles -- 全局css样式
├── utils -- 工具类
└── views -- 前端页面
    ├── home -- 首页
    ├── layout -- 通用页面加载框架
    ├── login -- 登录页
    ├── oms -- 订单模块页面
    ├── pms -- 商品模块页面
    └── sms -- 营销模块页面

```

### 安装依赖

npm install

### 开发模式

npm run dev

### 生产部署

npm run build
