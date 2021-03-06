# 前言

 
## 写作背景

　　我一直想写一本关于分布式系统方面的书。一方面是想把个人多年工作中涉及的分布式技术做一下总结，另一方面也想把个人的经验分享给广大的读者朋友。由于我的开发工作大都以Java为主，所以一开始的主题设想是"分布式Java"，书也以开源方式发布在互联网上（网址为https://github.com/waylau/distributed-java）。

　　后来，陈晓猛编辑看到了这本开源书，以及我关于分布式系统方面的博文，问我是否有兴趣出版分布式相关题材的图书。当然书的内容不仅仅是"分布式Java"。

　　对于出书一事，我犹豫良久。首先，本身工作挺忙，实在无暇顾及其他；其次，虽然我之前写过超过一打的书籍（可见https://waylau.com/books/），但多是开源电子书，时间、内容方面自然也就不会有太多约束，几乎是"想写就写，没有时间就不写"，这个跟正式出版还是存在比较大的差异的；最后，这本书涉及面相对较广，需要查阅大量资料，实在是太耗费精力。

　　但陈晓猛编辑还是鼓励我能够去尝试做这个事情。思索再三，于是我便答应。当然，最后这本书还是在规定时间内完成了。它几乎耗尽了我写作期间所有的业余和休息时间。

　　"不积跬步，无以至千里；不积小流，无以成江海。"虽然整本书从构思到编写完成的时间不足一年，但书中的大部分知识点，却是我在多年的学习、工作中积累下来的。之所以能够实现快速写作，一方面是做了比较严格的时间管理，另一方面也得益于我多年坚持写博客和开源书的习惯

## 内容简介

　　本书分为三大部分，即分布式系统基础理论、分布式系统常用技术以及经典的分布式系统案例分析。第一部分为第1章和第2章，主要介绍分布式系统基础理论知识，总结一些在设计分布式系统时需要考虑的范式、知识点以及可能会面临的问题。 第二部分为第3章到第8章，主要列举了在分布式系统应用中经常用到的一些主流技术，并介绍这些技术的作用和用法。第三部分为第9章和第10章，选取了以淘宝网和Twitter为代表的国内外知名互联网企业的大型分布式系统案例，分析其架构设计以及演变过程。

* 第1章介绍分布式系统基础理论知识，总结一些在设计分布式系统时需要考虑的范式、知识点以及可能会面临的问题，其中包括线程、通信、一致性、容错性、CAP理论、安全性和并发等相关内容。
* 第2章详细介绍分布式系统的架构体系，包括传统的基于对象的体系结构、SOA，也包括最近比较火的RESTful风格架构、微服务、容器技术、Serverless架构等。
* 第3章介绍常用的分布式消息服务框架，包括Apache ActiveMQ、RabbitMQ、RocketMQ、Apache Kafka等。
* 第4章介绍分布式计算理论和应用框架方面的内容，包括MapReduce、Apache Hadoop、Apache Spark、Apache Mesos 等。
* 第5章介绍分布式存储理论和应用框架方面的内容，包括Bigtable、Apache HBase、Apache Cassandra、Memcached、Redis、MongoDB等。
* 第6章介绍分布式监控方面常用的技术，包括Nagios、Zabbix、Consul、ZooKeeper等。
* 第7章介绍常用的分布式版本控制工具，包括Bazaar、Mercurial、Git等。
* 第8章介绍RESTful API、微服务及容器相关的技术，着重介绍Jersey、Spring Boot、Docker等技术的应用。
* 第9章和第10章分别介绍以淘宝网和Twitter为代表的国内外知名互联网企业的大型分布式系统案例，分析其架构设计以及演变过程。


## 源代码

　　本书提供源代码下载，下载地址为 <https://github.com/waylau/distributed-systems-technologies-and-cases-analysis>。

## 勘误和交流

　　本书如有勘误，会在 <https://github.com/waylau/distributed-systems-technologies-and-cases-analysis> 上进行发布。由于笔者能力有限，时间仓促，难免错漏，欢迎读者批评指正。读者也可以到博文视点官网的本书页面进行交流（www.broadview.com.cn/30771）。

　　您也可以直接联系我：

* 博客：<https://waylau.com>
* 邮箱：<waylau521@gmail.com>
* 微博：<http://weibo.com/waylau521>
* 开源：<https://github.com/waylau>

## 致谢

　　首先，感谢电子工业出版社博文视点公司的陈晓猛编辑，是您鼓励我将本书付诸成册，并在我写作过程中审阅了大量稿件，给予了我很多指导和帮助。感谢工作在幕后的电子工业出版社评审团队对于本书在校对、排版、审核、封面设计、错误改进方面所给予的帮助，使本书得以顺利出版发行。

　　其次，感谢在我十几年求学生涯中教育过我的所有老师。是你们将知识和学习方法传递给了我。感谢我曾经工作过的公司和单位，感谢和我一起共事过的同事和战友，你们的优秀一直是我追逐的目标，你们所给予的压力正是我不断改进自己的动力。

　　感谢我的父母、妻子Funny和两个女儿。由于撰写本书，牺牲了很多陪伴家人的时间。感谢你们对于我工作的理解和支持。

　　最后，特别要感谢这个时代，互联网让所有人可以公平地享受这个时代的成果。感谢那些为计算机、互联网所做出贡献的先驱，是你们让我可以站在更高的"肩膀"上！感谢那些为本书提供灵感的佳作，包括《分布式系统原理与范型》《Unix Network Programming》《Enterprise SOA》《MapReduce Design Patterns》《Hadoop: The Definitive Guide》《Learning Hbase》《Advanced Analytics with Spark》《Pro Git》《Docker in Action》《淘宝技术这十年》《Hatching Twitter》，等等，详细的书单可以参阅本书最后的"参考文献"部分。 


柳伟卫

2016年11月13日于杭州
