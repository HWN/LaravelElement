# LaravelElement FOR havvan

这是一个Laravel(5.6)+VUE(2.*)+ElementUI(2.*)搭建的前后端分离框架,
已经配置好vue-router

## 环境
推荐使用Homestead
如果你执意要自己配置本地开发环境，那么你需要以下环境：

    PHP:^7.1.3
    Nginx
    Mysql(这取决于你后面的开发需求)
    Composer
    Node.js:^8.0.0

## 安装

#### 下载项目

    1. git clone https://github.com/HWN/LaravelElement.git

#### laravel 配置
    1. cp .evn.example .env

    2. composer install //laravel 相关依赖包安装

    3  本地开发域名配置我就不多废话了

---

#### vue 配置（VUE、Element-UI、vue-router）

    1. npm install // 速度慢的请自行切换淘宝镜像 cnpm
    
    2. npm run dev // 跑起来

##访问

    http://you-web-site/web#/hello