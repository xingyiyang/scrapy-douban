# scrapy-douban
通过学习慕课网的scrapy课程，抓取豆瓣排行榜250的数据

## 环境
windows 10，python3.6
https://www.lfd.uci.edu/~gohlke/pythonlibs/
下载scrapy（Scrapy‑1.5.1‑py2.py3‑none‑any.whl）和twisted（Twisted‑18.9.0‑cp36‑cp36m‑win_amd64.whl）轮子
安装pywin32： pip3 install pypiwin32

## 使用到的命令
scrapy startproject douban
scrapy genspider douban_spider
scrapy crawl douban_spider
scrapy crawl douban_spider -o test.json

## 使用到的mongodb命令
use douban;
show collections;
db.douban.find().pretty();

