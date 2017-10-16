# Python 数据处理方向考核任务

## 第一步：了解技术关键词

> 了解相关关键词，做 PPT 汇报，用自己的语言阐述概念和细节；估时 1-2 天

大方向关键词：

- 人工智能  -> 机器学习  -> 监督非监督学习 -> 神经网络 -> 深度学习 
- 大数据 -> 数据挖掘 -> 海量数据处理 -> 分布式处理算法

数据分析类关键词深入查询：

- 舆情分析关键词：自然语言处理、微博舆情、新闻涉警、事故预测
- 商品分析关键词：商品推荐、广告推荐、销量预测、报表分析

通过自主查询关键词获取信息，期望你能对这个方向有个大致了解，它到底是做什么的，该怎么做。

PPT 要求请参见 [统一要求](/#统一要求)。

## 第二步：安装开发环境

> 安装各项开发环境，为后续开发做基础；估时 1 天不到

需安装项：

1. Python3.6 运行时
2. PyCharm 2017 集成开发环境（并破解，当然有钱可以买正版）
3. Git 2.14 版本控制工具
   - 附可选安装：GitHub Desktop 或 Sourcetree 或 Tower
   - git 本身是命令行操作，后面三个软件是图形界面
   - OSX 下推荐使用 Tower

## 第三步：学习基础语法及工具使用

> 快速学习，人生苦短，考核任务没有那么多时间可以耗 :smirk:；估时 3 天

数据处理方向，首先要得有数据，所以本次考核任务小项目就是做一个能获取数据的简单爬虫。

因此对于python 基础语法，应掌握到足够支持完成一个简单爬虫程序，包括知识点如下：

- Python 基础
  - 数据类型和变量
  - 字符串和编码
  - 使用 list 和 tuple
  - 条件判断
  - 循环
  - 使用 dict 和 set
- Python 函数
  - 调用函数
  - 定义函数
  - 函数的参数
  - 递归函数
- 模块化，对象化
  - 使用模块
  - 类和实例
  - 访问限制
  - 继承
  - 实例属性和类属性
- 基础库
  - urllib
  - 可选 beautifulsoup 和 scapy

参考链接：

1. [廖雪峰 Python3 教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)
2. [Python3 中文手册](http://docs.pythontab.com/python/python3.5/)



对于 GitHub，需要掌握 

- 版本控制概念
- git 基本使用（add, check, commit, push）
- GitHub 用户注册、仓库建立、本地关联、上传代码

参考链接：

1. [廖雪峰 Git 教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
2. [图解 GitHub 和 SourceTree 入门教程](http://blog.csdn.net/collonn/article/details/39259227)
3. [GitHub Desktop 使用方法](http://blog.csdn.net/harryptter/article/details/51363473)
4. [Tower](https://www.git-tower.com/windows/)

## 第四步：简单的网络爬虫

> 开始开发本次任务设定的小项目，能够获取数据的爬虫；估时 3 天

1. 实现爬虫基本的数据获取功能，即对某个网页，能获取到多个页面内有价值的信息，并保存
2. 可以是爬图片或文字，对象任意，无限制
3. 有数据库基础的可以存到数据库中，否则存到本地文本文件
4. 源码放在 GitHub 仓库上，爬取结果不上传
5. 爬取结果可部分截图放在 README 中作为展示
6. 验收时展示爬取结果，再讲解 GitHub 上源代码

## 第五步：审核验收

> ​:sunglasses: 恭喜完成

展示成果，再看过程

讲解思路，再看代码

规范你的代码，Python 有官方的代码风格指南 [PEP8](https://www.python.org/dev/peps/pep-0008/)，不要在审核代码的时候污染眼睛

任务完成。
