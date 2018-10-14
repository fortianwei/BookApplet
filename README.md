# 小说阅读  微信小程序

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
![](https://github.com/moxier/BookApplet/blob/master/img/04.png)
![](https://github.com/moxier/BookApplet/blob/master/img/05.png)
![](https://github.com/moxier/BookApplet/blob/master/img/06.jpg)
