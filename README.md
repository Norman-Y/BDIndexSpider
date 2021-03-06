# BDIndexSpider

百度指数抓取工具

提供关键词、起始和结束日期、地区，软件能够抓取多个关键词每天的百度指数

> 请仔细阅读本文档说明，一些简单的问题自己查，别人没义务为你解答

### Feature

- 支持按照**省份、城市**查询
- 目前仅支持**PC+移动**趋势指数数据抓取
- 实测兼容**Mac**、**Windows**系统，理论上也支持**Linux**，但没测过

### Requirement

- 源码基于Java1.8
- 使用Maven管理

### 使用说明

- 运行前，需要在左上角初始化中**配置账户密码**和导入要抓取的**关键词**
- 需要安装**Chrome**浏览器，版本在**69-71**之间
- 源码中的`a.txt`为输入文件格式要求，可以**输入多行**
- 如果不想运行源码，可以到**executable**目录下直接下载可执行`jar`文件

### 常见问题

关于工具的问题反馈和建议，推荐大家在github上开[issue](https://github.com/songgeb/BDIndexSpider/issues)进行详细说明

PS: 像**如何运行jar**、**在哪里下载**这种问题建议自己网上查查，多翻翻文档

#### 启动后总是初始化失败
1. 使用管理员权限运行`jar`试一下
2. 检查下账号密码和关键词是否已设置

### ChangeLog

- 2018年11月06日
	- 适配新的百度指数页面，新版页面不再需要下载图片+图像识别
	- 速度会更快，但尚不清楚是否会有频率限制问题
- 2018年05月11日
	适配新的百度指数页面
- 2018年04月22日
	加入按照地区查询功能
- 2018年04月13日
	不再使用tesseract进行ocr，自己写了个ocr实现

- 2018年04月08日
	提高精确模式抓取效率

- 2018年04月05日
	添加可执行jar文件，添加用户可配置账户密码功能

- 2018年04月01日
	目前已经修复了**精确模式**，可以正常运行

- 2018年03月27日
	本代码写于2016年，首次开源，目前由于Webdriver驱动的问题，无法直接运行。后面会抽时间修复一下

### 打赏

<div align=center>
<div style="display:inline-block;">
<img src="https://songgeb.github.io/images/wechat.jpg">
<p>微信</p>
</div>

<div style="display:inline-block;">
<img src="https://songgeb.github.io/images/alipay.jpg">
    <p>支付宝</p>
</div>
</div>
