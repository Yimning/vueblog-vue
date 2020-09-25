# vue-hello

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
``` 
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


    进入 src 文件夹，这是实际都工程文件夹，其他文件夹以及文件以后在了解。
    

    3个文件夹  assets - 各类静态资源文件夹 - 比如 图片, css 文件等。  components - 组件文件夹, 组件是 vue 等 MVC 框架等核心概念，自行了解含义。 view - 视图文件夹。
    

    5个文件  app.vue、main.js - 主视图、配合 main.js 成为 vue 程序的主入口。router.js - 路由程序主入口。store.js - 路由状态管理系统。
    

    registerServiceWorker.js 暂不进行了解。 
    

    介绍完工程文件夹，进入本文主要关注点 - 组件。
    

    *.js 和 *.vue文件都可以单独成为 组件 。我不会使用单独的 *.js 文件作为组件 ( 用 *.vue 文件作为组件方便理解和管理 )。组件可以单独用 *.vue 写出来，也可以分开同时用 *.vue 和 *.js 来完成一个或者多个组件。
    

    当前工程文件夹中存在 4 个组件：app.vue + main.js、helloworld.vue、views/home.vue、views/about.vue。
    

    template 标签：4 个组件都有，这是渲染模版，也是组件的核心，细心的读者可以发现这4个 template 中都包含有一个顶层都 div 元素。script 标签：helloworld.vue 和 views/home.vue 中有，也可以用单独的 js 文件描述，比如 main.js。style 标签：app.vue 和 helloworld.vue 中有，提供【组件作用域】的 css 样式，防止团队协同开发导致的 css 样式名冲突。
