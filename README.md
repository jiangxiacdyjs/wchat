# WChat By Vue 2.x

## 项目说明

- **由于服务器太久没维护，所以实际的登录、聊天等功能都尚不可用；**
- **该项目目前正在进行重构，主要是优化代码质量，更合理地去使用Vue的整个生态功能；**
- **新增数据`mock`功能，在实际的项目开发过程中`mock`十分重要；**

该项目算是我个人成长过程中的一些经验总结，由于工作确实比较忙，也很久没有更新了。现在对于`Vue`或者说前端都有很多更深的认识，所以想尽可能的把自己所学的知识、工作经验通过这个项目展现出来。

暂时先摒弃**后端**这一块，专注于前端，假如后面还有时间再重构后端代码。

> ~~WChat 是一款模仿iOS端微信的 Web App，具有真实的聊天等功能，并采用前后端分离的方式来实现。前端基于 Vue 2.0 框架，[后端](https://github.com/moohng/wchat-sv)基于 Node.js + Express + MongoDB，聊天功能和添加好友功能通过 Websocket 实现。~~

> 前端技术栈: vue 2.x、vue-cli、vuex、vue-router、webpack 3.x、sass、babel、mock等；

> ~~后端技术栈：Node.js、Express、express-session、WebSocket(ws)、MongoDB、mongoose、ES6等。~~

## 在线预览

~~[点击这里在线查看效果](http://mohng.com/wchat-vue)，建议使用谷歌浏览器，并开启手机调试模式（由于项目仍在开发中，部分功能可能不是最新、或暂不可用）。~~

~~新用户必须通过注册账号进入，已注册用户可直接登录进入。目前占不支持离线消息，也不支持添加离线用户为好友（即时通信相关功能必须保证对方在线）~~

## 本地使用

建议使用谷歌浏览器并在手机调试模式下查看(http://localhost:8808/)。

``` bash
# clone
$ git clone https://github.com/moohng/wchat-vue.git

# 进入到目录 并安装所有依赖（建议修改成淘宝镜像）
$ cd wchat-vue
$ yarn

# 启动本地服务 监听8808端口
$ yarn dev
```

`node-sass`安装失败的解决办法：

``` bash
$ yarn add node-sass -D --sass_binary_site=https://npm.taobao.org/mirrors/node-sass
```

或

``` bash
$ yarn config set sass_binary_site https://npm.taobao.org/mirrors/node-sass
$ yarn add node-sass -D
```

## 效果演示

### 登陆

![Login](http://moohng.oss-cn-shenzhen.aliyuncs.com/wchat/login.gif)

### 注销

![Logout](http://moohng.oss-cn-shenzhen.aliyuncs.com/wchat/logout.gif)

### 聊天

![Chat](http://moohng.oss-cn-shenzhen.aliyuncs.com/wchat/chatroom.gif)

### 添加好友

![add friend](http://moohng.oss-cn-shenzhen.aliyuncs.com/wchat/add-friend.gif)

## 功能说明

~~该项目已实现后端服务器的支持，具有真实的聊天功能。后端部分请转移[这里](https://github.com/moohng/wchat-sv)~~

- ~~高仿iOS端的界面设计风格，具有push、pop、modal、dismiss等转场动画；~~
- ~~注册、登陆和注销功能，可记住登录状态，避免多次登录；~~
- ~~聊天室功能，所有在线用户可进行群聊；~~
- ~~添加好友，目前必须保证对方在线才能正确添加；~~
- ~~用户私聊，目前必须保证对方在线方可正常聊天；~~
- ~~目前只支持纯文本聊天。~~

更多功能请待续...

如果您觉得该项目不错, 欢迎**star**和分享！
