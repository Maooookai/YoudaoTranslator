# 有道翻译爬虫工具

###### 支持将txt文本按行翻译，默认为自动检测语言

### 用法（Windows）

使用前注意Chrome版本，如果不对请前往
[此链接](http://npm.taobao.org/mirrors/chromedriver/)
下载对应的chromedriver.exe



下载最新的release，将待翻译文件放在同级目录，在终端/CMD中输入
```
.\main.exe .\trans.txt
```
会在同级目录下生成基于时间命名的翻译结果，可同时运行多个。但频率过高容易被检测
### 导入

本工具用到了selenium库，导入前注意解决需求问题