```
label:#文本分析 #爬虫 #初级  
```  
***
简介  
爬取B站视频‘那年那兔那些事儿’的弹幕数据以及相关用户ID，并进行数据分析
***
目录
- 1.[爬取b站弹幕数据与用户信息](scraping/collect_users.ipynb)   
实现：  
    - BeautifulSoup、lxml、正则表达式爬取弹幕内容、用户id
    - 爬虫静态文件获取、认证授权，逆向解码整理用户id
    - 随机森林重新采样  
缺点： 
    - 
- 2.[分析弹幕数据](analyse/text_analyse.ipynb)   
实现：  
    - jieba库去除空值、停用词，并分词
    - TF-IDF法分析关键词，wordcloud库生成词云
    - seaborn库分析弹幕年日时间频  
缺点：
    - 缺乏情感分析、数据挖掘
    - 
***
