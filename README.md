# 为什么有了LUCENE还要ES呢?
1.LUCENE只是一个JAVA语言的全文检索库,配置使用复杂,且不支持集群环境,大项目不友好.<br/>
2.跟应用服务器共用一台机器,如果再加上数据库数据,导致磁盘压力大.<br/>
因此,项目中需要有一个所有语言通用且简单免费的全文检索工具,这就是ES的价值.<br/>
*ES是分布式实时文件存储的全文检索服务器,每个字段都被索引并可搜索<br/>
*分布式的实时分析搜索引擎<br/>
*可以扩展到上百台服务器处理PB级别的结构化和非结构化数据<br/>
*高度集成化的服务,可以通过简单的RESTFUL API,各种语言的客户端甚至命令行与之交互<br/>
<br/><br/><br/>
ES官网地址:https://www.elastic.co/
