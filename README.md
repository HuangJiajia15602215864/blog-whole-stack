### blog-whole-stack


#### 技术栈
- react
- express
- MongoDB
#### 项目目录
```
├── README.md                   //项目说明文件
├── app                         //前端源码文件夹
│   ├── components              //前端组件文件夹
│   ├── configureStore.js       //配置store文件
│   ├── containers              //前端容器组件文件夹
│   ├── fetch                   //封装get/post请求文件夹
│   ├── index.js                //APP输出文件
│   ├── lib                     //存放第三方引入文件文件夹
│   ├── reducers                //reducer文件夹，包含actions、actionTypes
│   └── sagas                   //saga文件夹,异步action处理
├── config                      
│   └── config.js               //总应用配置文件
├── db                          //存放数据库的文件夹
├── modules                     //存放mongoose model文件夹
│   └── user.js                 //存放user model文件
├── package.json
├── postcss.config.js           //postcss配置文件
├── record                      //存放一些记录文件的文件夹
├── schemas                     //mongoose schema文件夹
│   └── users.js
├── server                      // server端源码文件夹
│   ├── api                     //server端 api接口文件夹
│   ├── index.js                //server启动文件
│   ├── server.js               //server文件
│   └── util.js                 //server端工具类文件
├── static                      //静态资源托管文件夹
│   └── favicon.ico
├── webpack.dev.js              //开发环境下webpack配置文件
└── webpack.prod.js             //生产环境下webpack配置文件

```