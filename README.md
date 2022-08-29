# elm-fake

## Project setup
### 请确保node的版本为node14，否则node-sass安装报错

```
npm install 或 yarn
```

### Compiles and hot-reloads for development
```
npm run dev 
```

## 项目目录结构
```
├── src                                         // 源码目录
│   ├── components                              // 公共组件
│   ├── config                                  // 基本配置（Fetch获取数据和其他工具类）
│   ├── images                                  // 公共图片
│   ├── page                                    // 页面
│   │   ├── city                                // 当前城市
│   │   ├── confirmOrder                        // 订单提交
│   │   ├── food                                // 食品筛选排序           
│   │   ├── forget                              // 修改密码
│   │   ├── home                                // 首页
│   │   ├── login                               // 登录注册页
│   │   ├── msite                               // 商铺列表页
│   │   ├── order                               // 订单
│   │   ├── profile                             // 个人中心
│   │   ├── search                              // 搜索页
│   │   ├── shop                                // 商铺详情
│   ├── router
│   │   └── router.js                           // 路由配置
│   ├── service                                 // 数据交互统一调配
│   │   ├── getData.js                          // 获取数据的统一调配文件，对接口进行统一管理
│   │   └── tempdata                            // 临时数据
│   ├── store                                   // vuex的状态管理
│   └── style
│       ├── common.scss                         // 公共样式文件
│       ├── mixin.scss                          // 样式配置文件
│   ├── App.vue                                 // 页面入口文件
│   ├── main.js                                 // 程序入口文件，加载各种公共组件
```

## 后端接口详见：https://github.com/bailicangdu/node-elm/blob/master/API.md

###	其他事项

### 部分运行截图


<img src="https://github.com/BirdGurhl/elm-fake/blob/master/screen%20shots/run.gif" width="316" height="685"/>
