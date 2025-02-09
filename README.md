![](https://github.com/realguoshuai/hadoop_study/blob/master/hadoop%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/hadoop/index.jpg)
## hadoop 
* [hadoop科普](https://github.com/realguoshuai/hadoop_study/wiki/%E7%A7%91%E6%99%AEHadoop)
* [大数据书籍](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E6%95%B0%E6%8D%AE%E4%B9%A6%E7%B1%8D)
* [大数据学习路线图](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF)
#### hadoop 导图笔记
* [hadoop伪分布式搭建](https://github.com/realguoshuai/hadoop_study/tree/master/hadoop%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/hadoop/hadoop%E9%9B%86%E7%BE%A4%E6%90%AD%E5%BB%BA)
* [hadoop介绍](https://github.com/realguoshuai/hadoop_study/tree/master/hadoop%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/hadoop/hadoop%E7%A7%91%E6%99%AE)
* [hadoop经典面试题及解题思路](https://github.com/realguoshuai/hadoop_study/tree/master/hadoop%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE/hadoop/%E9%9D%A2%E8%AF%95%E9%A2%98)
## hive
*  [阅读官方文档](https://github.com/realguoshuai/hadoop_study/wiki/hadoop%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91)
*  [导图笔记](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E7%89%9BBlog)
*  [hive必会50道sql](https://github.com/realguoshuai/hadoop_study/wiki/hadoop%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91)
*  [hive开窗函数](https://blog.csdn.net/wangpei1949/article/details/81437574)
*  hive基本是大数据入门必学的,在离线计算用的比较多,市场需求大,有sql基础入门比较快
### Scala
*  [阅读官方文档](https://yq.aliyun.com/topic/69?utm_content=m_17543)
*  [导图笔记](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E7%89%9BBlog)
*  scala 工作中flink/spark代码一般都是使用 Scala 实现 优先学!  
## Spark
*  [阅读官方文档](https://yq.aliyun.com/topic/69?utm_content=m_17543)
*  [导图笔记](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E7%89%9BBlog)
#### SparkSQL
*  [Spark同步hive数据到solr](https://github.com/realguoshuai/hadoop_study/tree/master/Spark2x/mtdap-sparksql)
#### Spark Structured Streaming
*  后台我已经使用flink替代掉
## Flink
*  [总结文档](https://github.com/realguoshuai/hadoop_study/blob/master/Flink/%E6%96%87%E6%A1%A3/Flink%20%E5%88%9D%E8%AF%86.txt)
*  [Flink 常见QA](https://github.com/realguoshuai/hadoop_study/tree/master/Flink/QA)
*  [Flink开发者资料](https://ververica.cn/developers-resources/)
*  [Flink 阿里直播(每周四晚20:00-21:00))](https://github.com/flink-china/flink-training-course/)
*  [不搭建环境,使用socket代码模拟kafka数据源 进行flink流处理](https://github.com/realguoshuai/hadoop_study/tree/master/Flink/Flink%E9%A1%B9%E7%9B%AE/flink%2Bsocket%E5%AE%9E%E7%8E%B0%E6%B5%81%E5%BC%8FWC)
*  [Flink示例代码-实时计算违反尾号限行车辆](https://github.com/realguoshuai/hadoop_study/blob/master/Flink/Flink%E9%A1%B9%E7%9B%AE/flink-rtc-tailnumlimit/src/com.guoshuai/realtime/details/TailNumVioDetails.scala)
*  [Flink电商Demo-用户行为实时分析](https://github.com/realguoshuai/UserBehaviorAnalysis)
*  [Flink接入socket实时数据源实现热门商品topN写入es](https://github.com/realguoshuai/hadoop_study/blob/master/Flink/FlinkDemo/SocketFlinkEs/LogAnalysis2Es.scala)
*  [Flink Table Demo 基于1.7.0+](https://github.com/realguoshuai/hadoop_study/tree/master/Flink/FlinkDemo/table)
*  真.流计算利器,但是资料比较少,建议直接看官方文档 我会将自己的翻译的文档和bug的解决方式不定期上传到Flink的对应目录下
*  Flink开发满一年了 公司从无到有 现在日常使用flink进行简单的实时ETL && 实时指标汇总 && 实时预警  上线了交通类近20个job
   不足:主要是写业务函数+简单算子,深点的东西还是没应用过(比如cep state api) 才刚开始 
### HBase(phoenix)
*  [文档笔记](https://github.com/realguoshuai/hadoop_study/tree/master/HBase) 
*  [phoenix 自定义UDFs函数](https://github.com/realguoshuai/hadoop_study/tree/master/HBase/Phoenix%E8%87%AA%E5%AE%9A%E4%B9%89%E5%87%BD%E6%95%B0UDF)
*  见HBase目录,不定期更新
## kafka
*  [阅读官方文档](https://github.com/realguoshuai/hadoop_study/wiki/hadoop%E7%A4%BE%E5%8C%BA%E5%AE%98%E7%BD%91)
*  [导图笔记](https://github.com/realguoshuai/hadoop_study/blob/master/Kafka/%E5%8D%B0%E8%B1%A1%E7%AC%94%E8%AE%B0%E6%88%AA%E5%9B%BE.png)
*  开源的消息队列,流计算架构一定要有的一个组件
## redis
*  [Redis命令参考](//http://doc.redisfans.com/)
*  [导图笔记](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E7%89%9BBlog)
## solr
*  [阅读官方文档](http://lucene.apache.org/solr/6_2_0/solr-core/overview-summary.html)
*  [导图笔记](https://github.com/realguoshuai/hadoop_study/wiki/%E5%A4%A7%E7%89%9BBlog)
*  全文检索 solr+kerberos验证(巨坑,文档稍后上传)
*  solr 实时创建索引延迟问题 (增量3000-4000w/天)
*  [solr百亿规模数据优化](https://github.com/realguoshuai/hadoop_study/tree/master/Solr)
*  [结巴分词](https://github.com/realguoshuai/hadoop_study/tree/master/Solr/Jieba%E5%88%86%E8%AF%8D)
## Eleasticsearch
*  占坑,可以直接使用dbms+es实现几千万数据可视化展示 汇总,底层跟solr一样,都是基于lucene 
*  [ES6.1.3集群搭建(+jdk1.8.0_131)](https://github.com/realguoshuai/hadoop_study/blob/master/ELK/ElasticSerach6.1.3/Es%E9%9B%86%E7%BE%A4%E6%90%AD%E5%BB%BA.txt)
*  [ES性能优化-转载](http://www.aboutyun.com/thread-27026-1-1.html)
*  [ES代码-入库查询](https://github.com/realguoshuai/hadoop_study/tree/master/ELK/ElasticSerach6.1.3/%E4%BB%A3%E7%A0%81/mtdap-elastic)
*  [SpringBoot实现ES服务化,提供rest接口]()
## MongoDB
## Kylin
## kerberos
*  [印象笔记](https://github.com/realguoshuai/hadoop_study/tree/master/Kerberos)
*  主要分为人机/机机认证,大数据环境安装kerberos认证后,所有组件互通都需要互相认证,对开发有不小挑战 
*  2019-5-5 更新 Fusioninsigh下的所有组件互通已经调试好 
### springboot 
*  [示例模板](https://github.com/realguoshuai/hadoop_study/tree/master/SpringBoot/HelloWorld%E6%A8%A1%E6%9D%BF/spring-boot-hello)
*  大数据开发,有能力的还是要学一下,数据服务化不求人(个人感觉,如果不懂代码,把这个交给应用层开发,性能没有优化,用户体验是真的差) 
*  已经实现了solr和es对上层提供的rest接口
#### 持续更新...
* 会不定期的将在工作中接触大数据组件时做的去敏测试代码上传到对应的文件夹下供初学者参考,少走弯路    包括自己每天更新的大数据印象笔记  更新的进度和规划在issues 中
* 今年计划重心是在实时计算上Flink,下半年的规划 : sparksql或flinksql  flinksql推荐使用1.7.0+  
* 最新工作 : Solr出现问题(从存量50亿查当天数据,晚上查询30-50s,早上2s),50亿数据,查一天的最后一页,内存一下满了导致的(最后一页用户非得留着)
* 今天用到了jieba分词,需要自定词库+solr来获取警情的空间经纬度坐标(已实现,代码测试去敏后上传)
* es+kerberos https证书卡着了(已解决,需要用华为二次开发的jar),先将DSL语法熟悉下上传   
* 这两天调试spark同步hive到es程序,es是kerberos安全认证的,网上的都是http的方式访问,难受,最终使用jdbc的方式在安全模式的集群下从hive读数据到es ok
 断断续续优化的flink程序  加入rebalance,解决数据倾斜,导致背压,优化背压 对过车时间进行取余处理进行分流... 最终发现优化需要减操作步骤  而不是增加!!
 跑了两天 离线程序白天还在跑导致CPU负载很高 实时计算程序受到影响  
 * 优化实时计算代码(代码开发很简单,数据量一上来就算不过来) 原因:内存隔离 CPU共享  50亿+solr 查询导致集群CPU负载高
 * solr分库后 高CPU的现象解决 遗留问题:程序定时删除出bug  
 * 最近任务 开始 es 服务化  替代现有的solr 一天搞定
 * flink table api ok,公司使用flink state api 功能很方便 但是开发复杂,测试demo代码后面上传
 * 出差 停更一周
