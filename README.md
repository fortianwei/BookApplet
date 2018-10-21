﻿# 小说阅读  微信小程序

说明
--
小程序，后端使用 Flask 框架提供 api 功能，用户权限管
理 和 爬虫功能，并将书籍数据和用户信息数据保存于Mysql数据库，前端使用
mpvue框架开发的微信小程序前端页面与后端资源进行交互。


下载
--
```shell
git clone https://github.com/moxier/BookApplet.git
```
1. 请修改books\server\novel\app\config\secure.py
```python
# APPID
APPID = "xxxx"

# SECRET
APP_SECRET_KEY = "xxx"
```


2. 在`books`目录下执行
```shell
npm install
```


3. 在`books/server`目录下(需要安装`pipenv`)
```shell
pipenv install
```


4. 开启`server`端
```shell
python novel.py
```


5. 运行小程序
```shell 
npm run dev
```


效果图
--
![](https://github.com/moxier/BookApplet/blob/master/img/01.png)

![](https://github.com/moxier/BookApplet/blob/master/img/02.jpg)

![](https://github.com/moxier/BookApplet/blob/master/img/03.jpg)

![](https://github.com/moxier/BookApplet/blob/master/img/07.png)

![](https://github.com/moxier/BookApplet/blob/master/img/08.png)

![](https://github.com/moxier/BookApplet/blob/master/img/04.png)

![](https://github.com/moxier/BookApplet/blob/master/img/05.png)

![](https://github.com/moxier/BookApplet/blob/master/img/06.jpg)


最后
--
虽然代码很渣，小程序也还有部分没有完成，但经过这次的练习，自己感觉还是有不少的收获的，希望自己能不断进步吧！