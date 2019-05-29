<b>小爱xx管理系统</b>

**A magical vue element touzi admin.**

- [效果演示地址](http://www.jiouai.com/permission/#/login)

**分支说明：**

**master分支**：前后端统一开发的版本；可以用于学习nodejs+mongodb+express相关知识；

**dev分支**：进行了前后端分离的版本；用户只关注于前端部分，可忽略服务端；下载下来，即可运行；

**dev-permission分支**：增加了权限管理(包括页面权限和按钮权限)的功能；同时将项目进行了重构；

## About

本文主要讲解dev-permission分支内容：


```bash
  如果对您对此项目有兴趣，可以点 "Star" 支持一下 谢谢！ ^_^
  
  或者您可以 "follow" 一下，我会不断开源更多的有趣的项目
  
  开发环境 windows 64 、nodejs 6.11.0
  
  如有问题请直接在 Issues 中提，或者您发现问题并有非常好的解决方案，欢迎 PR
```

## 技术栈

**前端技术栈：** vue2 + vuex + vue-router + webpack + ES6/7 + less + element-ui

**服务端技术栈：** easy-mock,mockjs

## 参考文档

easy-mock使用，请参考[官方文档](https://easy-mock.com/docs);

mockjs使用，请参考[官方文档](https://github.com/nuysoft/Mock/wiki/Getting-Started);

## 前序准备

**运行前准备：**

   由于此项目是基于nodejs的前后端结合项目，你需要进行nodejs的相关准备工作。项目运行之前，请确保系统已经安装以下应用：
   
   (1)、node (6.0 及以上版本)。使用细节，请参考：[node的下载及安装。](https://nodejs.org/en/download/)
        

## 开发：
git clone -b dev-permission https://github.com/wdlhao/vue2-element-touzi-admin  (注意：要从dev-permission分支拉取代码)

cd vue2-element-touzi-admin

npm install

**本地运行：**

**npm run dev** 运行之后，会默认打开本地访问路径：http://localhost:8012

**发布：**

**npm run bulid** (生成打包之后的项目文件,此文件主要用于项目部署)。

## 演示
测试账号:

1. username: admin
   password: 123456
2. username: editor
   password: 123456

注意：

admin拥有最高权限，可以查看所有的页面和按钮；

editor只有被赋予权限的页面和按钮才可以看到；


## [查看更多demo](http://www.jiouai.com/permission/#/login)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/1.jpg)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/2.jpg)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/3.jpg)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/4.gif)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/5.gif)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/6.gif)
![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/master/exampleImgs/7.gif)

## 技术答疑，交流QQ群

欢迎添加群主微信：

![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/dev-permission/src/assets/img/wechat.jpg)

欢迎加入答疑qq群：

![image](https://github.com/wdlhao/vue2-element-touzi-admin/blob/dev-permission/src/assets/img/qq.png)