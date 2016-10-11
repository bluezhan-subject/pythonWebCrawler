# pythonWebCrawler
python 爬虫

### 知乎有一套打下去的爬虫教程

https://www.zhihu.com/topic/19577498


### Python爬虫入门

本文作者： 伯乐在线 - 崔庆才 
http://python.jobbole.com/81332/

### 几个点开始

根据我的经验，要学习Python爬虫，我们要学习的共有以下几点：

- Python基础知识
- Python中urllib和urllib2库的用法
- Python正则表达式
- Python爬虫框架Scrapy
- Python爬虫更高级的功能

#### urllib urllib2 urllib3

不要问我，我不知道，我现在用的是urllib3。

http://urllib3.readthedocs.io/


#### Scrapy

http://scrapy-chs.readthedocs.io/zh_CN/0.24/index.html  
http://scrapy-chs.readthedocs.io/zh_CN/1.0/index.html

发现大部分的资料都是 为Python2.7的版本整理的
而最新的Python3系列的没什么资料，没关系；
当我看到了 Scrapy 暂时不支持 Python3 瞬间 无感了。
看了很久之后：
   有人提出了： pip install scrapy==1.1.0rc1 
   Scrapy 推出了 1.1.0rc1 来支持 Python3系列；
不过我暂时没用不知道咋样~~~~ 等我用好......好吧，我已经卸载了 Python3.5 了。
最好就是重启电脑之后再安装其他版本。

待我使用一段 Python 2.7 之后 先~~~~~


#### 开始使用 Python2.7

现在的 Python 是 2.7.12
要用的 Scrapy 是 1.2.0 （已经支持 Python 2.7 or Python 3.3+）

安装 pip install scrapy 出错
是在过程中安装 pip install lxml 出了问题

是在是...........

我直接去down下来安装~~

#### 开始Scrapy

用 scrapy startproject project 来创建项目

目录为：

```JavaScript
 project/  //项目名字
    scrapy.cfg  //项目的配置文件
    project/
        __init__.py
        items.py
        pipelines.py
        settings.py
        spiders/  //储爬虫的目录
            __init__.py
            ...
```

#### 不想说了






