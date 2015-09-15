附录B  其他资源和参考资料
=======================================

前面的11章及附录A介绍了各式各样与Redis有关的议题。在使用Redis解决一个又一个问题的同时，本书也引入了一些读者可能不太熟悉的概念，并给出了这些概念的参考资料以便读者能够查找更多相关信息。

为了方便查找与本书介绍过的各个议题有关的软件、函数库、服务以及文档，这个附录综合了书中出现过的所有参考资料，并按照不同的议题对这些资料进行了分组。

B.1  提供帮助的论坛
--------------------------

如果读者在使用Redis或者阅读本书的过程中遇到困难的话，可以到以下论坛求助：

- https://groups.google.com/forum/#!forum/redis-db——Redis论坛
- http://www.manning-sandbox.com/forum.jspa?forumID=809——Manning出版社专门为《Redis实战》（Redis in Action）开设的论坛

B.2  入门议题
---------------------------

以下网站对Redis的基本信息以及使用方法进行了介绍：

- http://redis.io/——Redis的主网站
- http://redis.io/commands——完整的Redis命令列表
- http://redis.io/clients——Redis的客户端列表
- http://redis.io/documentation——这个页面列出了Lua脚本、发布与订阅、复制、持久化等特性的文档。
- http://github.com/dmajkic/redis/——Dusan Majkic移植的Windows版Redis
- http://github.com/MSOpenTech/redis/——微软官方移植的Windows版Redis

以下网站对Python的基本信息以及使用方法进行了介绍：

- http://www.python.org/——Python编程语言的主网站
- http://docs.python.org/——Python的文档主页
- http://docs.python.org/tutorial/——适合Python初学者阅读的Python文档
- http://docs.python.org/reference/——记录完整语法和语义细节的Python语言参考
- http://mng.bz/TTKb——生成器表达式
- http://mng.bz/I31v——Python模块教程
- http://mng.bz/9wXM——定义函数
- http://mng.bz/q7eo——可变参数列表
- http://mng.bz/1jLF——可变参数和关键字参数
- http://mng.bz/0rmB——List速构（comprehension）
- http://mng.bz/uIdf——Python生成器
- http://mng.bz/1XMr——函数装饰器以及方法装饰器

B.3  队列函数库以及一些其他用途的函数库
---------------------------------------------

- http://celeryproject.org/——Python编写的队列函数库，支持包括Redis在内的多种后端
- https://github.com/josiahcarlson/rpqueue/——只使用Redis后端的Python队列函数库
- https://github.com/resque/resque——使用Ruby编写的Redis队列函数库
- http://www.rabbitmq.com/——队列服务器，支持多种编程语言
- http://activemq.apache.org/——队列服务器，支持多种编程语言
- https://github.com/Doist/bitmapist——强大的Redis分析函数库，支持位图分析（bitmap-enabled analytics）

B.4  数据可视化和数据记录
----------------------------------

- http://www.jqplot.com/——需要配合jQuery使用的开源绘图函数库
- http://www.highcharts.com/——支持免费和商用两种模式的绘图函数库
- http://dygraphs.com/——开源的绘图函数库
- http://d3js.org/——通用的开源数据可视化函数库
- http://graphite.wikidot.com/——统计信息收集和可视化函数库

B.5  数据源
--------------------

本书在第5章使用了一个记录IP所属地的数据库，以下列出的网站给出了该数据库的来源，以及一些不清楚是否会定期更新的其他数据源：

- http://dev.maxmind.com/geoip/geolite——本书第5章用到的IP所属地信息
- http://www.hostip.info/dl/——可以免费下载和使用的IP所属地信息数据库
- http://software77.net/geo-ip/——另一个免费的IP所属地信息数据库

B.6  Redis经验分享和相关文章
-----------------------------------

- http://mng.bz/2ivv——这篇文章介绍了如何在多个数据中心之间进行带压缩功能的Redis复制
- http://mng.bz/LCgm——使用Redis实现实时更新
- http://mng.bz/UgAD——使用Redis字符串存储实时数据
- http://mng.bz/1OJ7——Instagram对在Redis里面存储大量键值对的经验分享
- http://mng.bz/X564——简单地总结了一些适合使用Redis来解决的问题，其中一部分问题在本书已经提到过了
- http://mng.bz/oClc——讲述了Craigslist是如何对Redis进行数据分片的
- http://mng.bz/07kX——讲述了一个在手机和电脑之间同步相片的应用是怎样在系统的各个方面使用Redis的
- http://mng.bz/4dgD——介绍了Disqus是怎样在生产环境中使用Redis的
- http://mng.bz/21iE——使用Redis存储RSS feed信息
- http://mng.bz/L254——一个早期的例子，介绍了如何使用Redis的列表来存储过滤后的Twitter消息
