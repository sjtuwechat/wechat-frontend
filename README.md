# wechat-frontend

> wechat-frontend

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
## 项目端口号
后端端口号为8080
前端对后端接口统一配置为http://127.0.0.1:8080


## 项目功能说明
1. 'pages/index/main' 二维码功能，支持扫描二维码获取事件、地点等信息；
点击"上传二维码信息"将相关信息上传至服务器，可选择事件和信息类型，进而点击"获取信息"按钮获取后台上传所有信息

2. 'pages/bluetooth/main' 蓝牙功能
实现蓝牙信息的获取、连接、断开、传送信息

3. 'pages/logs/main' 初始化空白页面

4. '^pages/picture/main' 上传文件功能，当前首页
目前可以选择类型，上传视频和图片；
可以获取当前服务器全部文件列表，进而选择下载



