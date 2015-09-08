.. Redis 实战 documentation master file, created by
   sphinx-quickstart on Tue Jun 24 13:59:13 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Redis 实战
======================================

.. image:: ria-cover.png
   :align: left
   :scale: 23

《Redis in Action》是由 Josiah Carlson 博士编写，
Manning 出版社出版的一本关于 Redis 应用方面的书籍，
该书深入浅出地介绍了 Redis 的五种数据类型，
并通过多个实用例子展示了 Redis 的用法，
除此之外，
该书还讲述了 Redis 的优化方法以及扩展方法，
是一本对于学习和使用 Redis 来说不可多得的参考书籍。

《Redis 实战》是《Redis in Action》一书的简体中文翻译版，
译者为黄健宏（huangz）。
**书本目前的翻译工作已经完成，
正在进行后续的排版和检查，
预计9月份就会印刷并出版。**

要了解本书的最新消息，
请定期访问本网站，
或者关注译者的\ `微博 <http://weibo.com/huangz1990>`_\ 、\ `豆瓣 <http://www.douban.com/people/i_m_huangz/>`_\ 、\ `twitter <https://twitter.com/huangz1990>`_\ 。


目录
------------------

- 序

- 前言

- 致谢

- 关于本书

  - 内容编排
  - 代码
  - 作者在线论坛

- 关于作者

- 关于封面插图

**第一部分：基础知识**

- 第1章 初识Redis

  - 1.1 Redis简介
  - 1.2 Redis数据结构简介
  - 1.3 Redis，你好！
  - 1.4 寻求帮助
  - 1.5 小结

- 第2章 使用Redis构建Web应用
  
  - 2.1 登录和cookie缓存
  - 2.2 使用Redis实现购物车
  - 2.3 网页缓存
  - 2.4 数据行缓存
  - 2.5 网页分析
  - 2.6 小结

**第二部分：核心概念**

- 第3章 Redis命令

  - 3.1 字符串
  - 3.2 列表
  - 3.3 集合
  - 3.4 散列
  - 3.5 有序集合
  - 3.6 发布与订阅
  - 3.7 其他命令
  - 3.8 小结

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

- 附录 A 快速安装指南
  
  - 在 Debian Linux 或者 Ubuntu Linux 上面安装 Redis 的方法
  - 在 OS X 上面安装 Redis 的方法
  - 在 Windows 上安装 Redis 的方法
  - 小试 Redis

- 附录 B 其他资源和参考资料

  - 提供帮助的论坛
  - 入门议题
  - 队列函数库以及一些其他用途的函数库
  - 数据可视化和数据记录
  - 数据源
  - Redis 经验分享和相关文章


作者简介
------------

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


译者简介
------------

黄健宏（huangz）在 2011 年开始接触 Redis 以来就一直在学习和研究 Redis ，
他从 Redis 2.4 开始阅读并追踪 Redis 的源码，
对 `Redis 2.6 <https://github.com/huangz1990/annotated_redis_source>`_ 以及 `Redis 3.0 <https://github.com/huangz1990/redis-3.0-annotated>`_ 的源码进行了详细的注释，
并通过分析源码创作了\ `《Redis 设计与实现》 <http://redisbook.com>`_\ 一书。

除此之外，
黄健宏还是 Redis 中文文档\ `《Redis 命令参考》 <http://RedisDoc.com>`_\ 的译者，
以及\ `《Redis 从入门到精通》课程 <http://www.chinahadoop.cn/course/53>`_\ 的讲师。

要了解关于《Redis 实战》译者黄健宏（huangz）的更多信息，
请访问他的个人主页 `huangz.me <http://huangz.me>`_ 。


相关资源
-----------

《Redis in Action》在 Manning 出版社的介绍页面：
http://www.manning.com/carlson/

《Redis in Action》书中的源码示例：
https://github.com/josiahcarlson/redis-in-action

《Redis in Action》在 
`亚马逊 <http://www.amazon.cn/Redis-in-Action-Carlson-Josiah-L/dp/1617290858>`_ 、 
`amazon.com <http://www.amazon.com/Redis-Action-Josiah-L-Carlson/dp/1617290858>`_ 
以及
`豆瓣 <http://book.douban.com/subject/10597898/>`_ 
的页面。
