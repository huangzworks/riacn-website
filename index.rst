.. Redis 实战 documentation master file, created by
   sphinx-quickstart on Tue Jun 24 13:59:13 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Redis实战
======================================

.. image:: ria-cover.png
   :align: right

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


购买方式
------------------

购买纸质书请访问以下网店：
`异步社区 <http://www.epubit.com.cn/book/details/4035>`_ 、
`京东 <http://item.jd.com/11791607.html>`_ 、
`当当 <http://product.dangdang.com/23800641.html>`_ 

购买电子书请访问以下网店：
`异步社区 <http://www.epubit.com.cn/book/details/4035>`_ 、

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

- `第 1 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch01_listing_source.py>`_
- `第 2 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch02_listing_source.py>`_
- `第 3 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch03_listing_source.py>`_
- `第 4 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch04_listing_source.py>`_
- `第 5 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch05_listing_source.py>`_
- `第 6 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch06_listing_source.py>`_
- `第 7 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch07_listing_source.py>`_
- `第 8 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch08_listing_source.py>`_
- `第 9 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch09_listing_source.py>`_
- `第 10 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch10_listing_source.py>`_
- `第 11 章相关源码 <https://github.com/huangzworks/riacn-code/blob/master/ch11_listing_source.py>`_
- `附录 A 相关源码 <https://github.com/huangzworks/riacn-code/blob/master/chA_listing_source.py>`_

又或者到 https://github.com/huangzworks/riacn-code 下载这些源代码。


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
请访问他的 `博客 <http://www.dr-josiah.com/>`_ 或者 `github <https://github.com/josiahcarlson>`_ 。


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
对 `Redis 2.6 <https://github.com/huangzworks/annotated_redis_source>`_ 以及 `Redis 3.0 <https://github.com/huangzworks/redis-3.0-annotated>`_ 的源码进行了详细的注释，
并通过分析源码创作了\ `《Redis 设计与实现》 <http://huangz.works/redisbook1e>`_\ 一书。

除此之外，
黄健宏还是 Redis 中文文档《Redis 命令参考》的译者。

要了解关于《Redis 实战》译者黄健宏的更多信息，
请访问他的个人主页 `huangz.works <http://huangz.works>`_ 。


相关资源
-----------

《Redis实战》用例目录，这篇文章逐一罗列了书中给出的各个 Redis 应用示例，以及这些示例的源码，方便读者参考： 
http://huangz.blog/2015/redis-usages-in-ria.html

..
        在线阅读《Redis实战》英文原版《Redis in Action》：
        https://redislabs.com/academy/redis-in-action

《Redis in Action》在 Manning 出版社的介绍页面：
https://www.manning.com/books/redis-in-action

《Redis实战》翻译记事，
这篇文章记录了《Redis实战》的诞生过程：
http://huangz.blog/2015/memories-of-redis-in-action-translation.html

《Redis实战》的豆瓣页面：
http://book.douban.com/subject/26612779/


勘误信息
----------------

..
    勘误信息页面列出了本书已确认的勘误信息， 
    请读者在阅读本书之前， 
    根据这些信息对书本进行校正， 
    由此带来的不便译者深感抱歉。

    如果读者发现了勘误页面目前尚未记录的新错误，

如果读者在阅读的过程中发现书本存在错误，
可以在本网站附带的 disque 论坛里面进行反馈，
又或者通过 `huangz.works <https://huangz.works>`_ 页面展示的任意一种联系方式来联系作者。


参加群讨论
----------------

欢迎各位《Redis命令参考》读者加入译者开设的 QQ 群，
你可以在里面分享你的 Redis 使用心得，
又或者跟其他群友讨论你在使用 Redis 过程中遇到的问题，
具体的群号请访问译者的\ `个人主页 <https://huangz.works>`_ 查看。
