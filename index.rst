.. Redis 实战 documentation master file, created by
   sphinx-quickstart on Tue Jun 24 13:59:13 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Redis实战
======================================

.. image:: ria-cover.png
   :align: left

欢迎来到《Redis实战》的支持网站！

《Redis实战》是《Redis in Action》一书的中文翻译版，
该书深入浅出地介绍了 Redis 的字符串、列表、散列、集合、有序集合等五种结构，
并通过文章聚合网站、cookie、购物车、网页缓存、日志、计数器、IP 所属地址查询程序、自动补全、分布式锁、计数信号量、任务队列、消息队列、搜索程序、广告定向程序、社交网站等一系列实用示例展示了 Redis 的用法。

除此之外，
《Redis实战》还介绍了使用短结构、分片、事务、流水线、复制、Lua 脚本等手段来扩展和优化 Redis 的方法，
这些技术可以大幅地扩展系统的性能，
并尽可能地降低程序所需的内存数量。

综上所述，
《Redis实战》将是一本对于学习和使用 Redis 来说不可多得的参考书籍，
无论是 Redis 新手还是有一定经验的 Redis 使用者，
应该都能从本书中获益。


购买方法
------------------

《Redis实战》将于 9 月底印刷，预计将于国庆之后在各大网店陆续上市，书本正式发售之后这里将贴出各个网店的购买链接。

另外还有《Redis实战》译者签名版可供购买，具体购买方法将于近日公布，敬请期待！


查看目录并试读
-------------------

《Redis实战》全书共 300 页，分为四个部分，包含 11 个章节和两个附录。

**以下目录中可点击的为试读内容。**

.. toctree::
   :maxdepth: 1
   
   preview/translator-foreword
   preview/foreword
   preview/preface
   preview/acknowledgments
   preview/about-this-book
   preview/about-the-cover

**第一部分：基础知识**

.. toctree::
   :maxdepth: 2

   preview/chapter1
   preview/chapter2

**第二部分：核心概念**

.. toctree::
   :maxdepth: 2

   preview/chapter3

- 第 4 章 数据安全与性能保障

  - 4.1 持久化选项
  - 4.2 复制
  - 4.3 处理系统故障
  - 4.4 Redis事务
  - 4.5 非事务型流水线
  - 4.6 关于性能方面的注意事项
  - 4.7 小结

- 第 5 章 使用Redis构建支持程序

  - 5.1 使用Redis来记录日志
  - 5.2 计数器和统计数据
  - 5.3 查找IP所属城市以及国家
  - 5.4 服务的发现与配置
  - 5.5 小结

- 第 6 章 使用 Redis 构建应用组件

  - 6.1 自动补完
  - 6.2 分布式锁
  - 6.3 计数信号量
  - 6.4 任务队列
  - 6.5 消息拉取
  - 6.6 使用 Redis 进行文件分发
  - 6.7 小结

- 第 7 章 基于搜索的应用程序

  - 7.1 使用 Redis 进行搜索
  - 7.2 有序索引
  - 7.3 广告定向
  - 7.4 职位搜索
  - 7.5 小结

- 第 8 章 构建简单的社交网站

  - 8.1 用户和状态
  - 8.2 定制时间线
  - 8.3 关注者列表以及正在关注列表
  - 8.4 状态消息的发布与删除
  - 8.5 流 API
  - 8.6 小结

**第三部分：进阶内容**

- 第 9 章 降低内存占用

  - 9.1 短结构
  - 9.2 分片结构
  - 9.3 打包储存二进制位和字节
  - 9.4 小结

- 第 10 章 扩展 Redis

  - 10.1 扩展读性能
  - 10.2 扩展写性能和内存容量
  - 10.3 对复杂的查询进行扩展
  - 10.4 小结

- 第 11 章 Redis 的 Lua 脚本编程

  - 11.1 在不编写 C 代码的情况下添加新功能
  - 11.2 使用 Lua 重写锁和信号量
  - 11.3 移除 WATCH/MULTI/EXEC 事务
  - 11.4 使用 Lua 对列表进行分片
  - 11.5 小结

**第四部分：附录**

.. toctree::
   :maxdepth: 2

   preview/appendx-a
   preview/appendx-b 


中文注释源码
------------------

为了帮助读者更好地学习《Redis实战》中附带的源代码，
译者将这些源代码的注释都翻译成了中文，
你可以在以下页面中在线阅读这些源代码：

.. toctree::
   :maxdepth: 1

   code-preview/chapter1.rst
   code-preview/chapter2.rst
   code-preview/chapter3.rst
   code-preview/chapter4.rst
   code-preview/chapter5.rst
   code-preview/chapter6.rst
   code-preview/chapter7.rst
   code-preview/chapter8.rst
   code-preview/chapter9.rst
   code-preview/chapter10.rst
   code-preview/chapter11.rst
   code-preview/appendx-a.rst

又或者到 https://github.com/huangz1990/riacn-code 下载这些源代码。


作者简介
------------

.. image:: dr_j.jpg
   :align: left

在大学毕业之后，
Josiah Carlson 博士继续在加州大学欧文分校学习理论计算机科学。
在学习之余，
Josiah 还断断续续地做过一些助教工作，
并偶尔承接一些编程方面的工作。
在 Josiah 即将要研究生毕业的时候，
他发现教职方面的工作机会并不多， 
于是他加入了 Networks in Motion 公司，
开始了自己的职业生涯。
在 Networks in Motion 公司期间，
Josiah 负责开发实时 GPS 导航软件，
以及交通事故通知系统。

在离开 Networks in Motion 公司之后，
Josiah 加入了 Google 公司，
之后他又到了 Adly 公司工作，
并开始学习和使用 Redis 来构建内容定向广告系统（content-targeting advertising）和 Twitter 分析平台。
几个月之后，
Josiah 加入了 Redis 邮件列表，
并在那里回答了数百个关于使用和配置 Redis 的问题。
在离开 Adly 公司并成为 ChowNow 公司的首席架构师兼联合创始人之后不久，
Josiah 开始创作这本《Redis 实战》。

要了解关于《Redis 实战》作者 Josiah Carlson 博士的更多信息，
请访问他的 `twitter <https://twitter.com/dr_josiah>`_ 、 `博客 <http://www.dr-josiah.com/>`_ 或者 `github <https://github.com/josiahcarlson>`_ 。


作序者简介
----------------

.. image:: antirez.jpg
   :align: left

Redis 的作者 Salvatore Sanfilippo 亲自为《Redis实战》撰写了序言。
他在序言中介绍了创作 Redis 的原因和经过，
回顾了这几年来 Redis 的发展，
并在最后向大家推荐了《Redis实战》这本书。

要了解 Salvatore Sanfilippo 的更多信息，
请访问他的个人主页： `invece.org <http://invece.org>`_ 。

|
|

译者简介
------------

黄健宏（huangz）在 2011 年开始接触 Redis 以来就一直在学习和研究 Redis ，
他从 Redis 2.4 开始阅读并追踪 Redis 的源码，
对 `Redis 2.6 <https://github.com/huangz1990/annotated_redis_source>`_ 以及 `Redis 3.0 <https://github.com/huangz1990/redis-3.0-annotated>`_ 的源码进行了详细的注释，
并通过分析源码创作了\ `《Redis 设计与实现》 <http://redisbook.com>`_\ 一书。

除此之外，
黄健宏还是 Redis 中文文档\ `《Redis 命令参考》 <http://RedisDoc.com>`_\ 的译者。

要了解关于《Redis 实战》译者黄健宏的更多信息，
请访问他的个人主页 `huangz.me <http://huangz.me>`_ 。


相关资源
-----------

在线阅读《Redis in Action》原版：
https://redislabs.com/academy/redis-in-action

《Redis in Action》在 Manning 出版社的介绍页面：
https://www.manning.com/books/redis-in-action

《Redis实战》的豆瓣页面：
http://book.douban.com/subject/26612779/

《Redis in Action》翻译记事，
这篇文章记录了《Redis实战》的诞生过程：
http://blog.huangz.me/diary/2015/memories-of-redis-in-action-translation.html


参加群讨论
----------------

欢迎各位《Redis实战》读者加入 Redis 技术讨论 QQ 群 398976550 ， 
你可以在群里面分享你的阅读心得和 Redis 使用经验，
又或者跟其他人讨论你在使用 Redis 过程中遇到的问题。
