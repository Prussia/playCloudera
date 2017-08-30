# CCAH

## [CCA Spark and Hadoop Developer Exam (CCA175)](http://cn.cloudera.com/more/training/certification/cca-spark.html)

## [Cloudera Developer Training for Spark and Hadoop](https://www.cloudera.com/more/training/courses/developer-training-for-spark-and-hadoop.html)

### CCAH

- Introduction to Apache Hadoop and the Hadoop Ecosystem
	- Apache Hadoop Overview
	- Data Storage and Ingest
	- Data Processing
	- Data Analysis and Exploration
	- Other Ecosystem Tools
	- Introduction to the Hands-On Exercises
- Apache Hadoop File Storage
	- Problems with Traditional
- Large-Scale Systems
	- HDFS Architecture
	- Using HDFS
	- Apache Hadoop File Formats
- Data Processing on an Apache Hadoop Cluster
	- YARN Architecture
	- Working With YARN
- Importing Relational Data with Apache Sqoop
	- Apache Sqoop Overview
	- Importing Data
	- Importing File Options
	- Exporting Data
- Apache Spark Basics
	- What is Apache Spark?
	- Using the Spark Shell
	- RDDs (Resilient Distributed Datasets)
	- Functional Programming in Spark
- Working with RDDs
	- Creating RDDs
	- Other General RDD Operations
- Aggregating Data with Pair RDDs
	- Key-Value Pair RDDs
	- Map-Reduce
	- Other Pair RDD Operations
- Writing and Running Apache Spark Applications
	- Spark Applications vs. Spark Shell
	- Creating the SparkContext
	- Building a Spark Application (Scala and Java)
	- Running a Spark Application
	- The Spark Application Web UI
- Configuring Apache Spark Applications
	- Configuring Spark Properties
	- Logging
- Parallel Processing in Apache Spark
	- Review: Apache Spark on a Cluster
	- RDD Partitions
	- Partitioning of File-Based RDDs
	- HDFS and Data Locality
	- Executing Parallel Operations
	- Stages and Tasks
- RDD Persistence
	- RDD Lineage
	- RDD Persistence Overview
	- Distributed Persistence
- Common Patterns in Apache Spark Data Processing
	- Common Apache Spark Use Cases
	- Iterative Algorithms in Apache Spark
	- Machine Learning
	- Example: k-means
- DataFrames and Spark SQL
	- Apache Spark SQL and the SQL Context
	- Creating DataFrames
	- Transforming and Querying DataFrames
	- Saving DataFrames
	- DataFrames and RDDs
	- Comparing Apache Spark SQL, Impala, and Hive-on-Spark
	- Apache Spark SQL in Spark 2.x
- Message Processing with Apache Kafka
	- What is Apache Kafka?
	- Apache Kafka Overview
	- Scaling Apache Kafka
	- Apache Kafka Cluster Architecture
	- Apache Kafka Command Line Tools
- Capturing Data with Apache Flume
	- What is Apache Flume?
	- Basic Flume Architecture
	- Flume Sources
	- Flume Sinks
	- Flume Channels
	- Flume Configuration
- Integrating Apache Flume and Apache Kafka
	- Overview
	- Use Cases
	- Configuration
- Apache Spark Streaming: Introduction to DStreams
	- Apache Spark Streaming Overview
	- Example: Streaming Request Count
	- DStreams
	- Developing Streaming Applications
- Apache Spark Streaming: Processing Multiple Batches
	- Multi-Batch Operations
	- Time Slicing
	- State Operations
	- Sliding Window Operations
- Apache Spark Streaming: Data Sources
	- Streaming Data Source Overview
	- Apache Flume and Apache Kafka
- Data Sources
	- Example: Using a Kafka Direct Data Source 
- Conclusion



Cloudera Developer training for Spark and Hadoop(CCA-175)课程介绍
Hadoop 及生态系统介绍    
•  传统大规模系统的问题   
•  Hadoop ！   
•  Hadoop 生态系统
Hadoop 体系结构及 HDFS   
•  机群环境下的分布式处理   
•  存储：HDFS 体系结构   
•  存储：使用 HDFS   
•  资源管理：YARN 体系结构   
•  资源管理：使用 YARN
使用 Apache Sqoop 导入关系数据   
•  Sqoop 简介   
•  数据的基本导入导出   
•  减少传输的数据量   
•  改善 Sqoop 性能   
•  Sqoop 2
Impala 及 Hive 介绍   
•  简介   
•  为什么使用 Impala 及 Hive   
•  Hive 和传统数据库的比较   
•  Hive 应用场景
使用 Impala 及 Hive 管理数据及建模   
•  数据存储   
•  创建数据库及表   
•  表数据导入   
•  HCatalog   
•  Impala 元数据缓存
数据格式   
•  选择文件格式   
• 支持不同文件格式的工具   
• Avro 数据格式定义模式   
• 在 Hive 及 Sqoop 里使用 Avro   
• Avro 格式数据模式变更   
• 压缩 数据分区   
• 分区概述   
• Impala 及 Hive 里的数据分区
Apache Flume 实时数据采集   
•  什么是 Apache Flume   
•  Flume 基本体系结构   
•  Flume 源   
•  Flume 槽   
•   Flume 通道   
•  Flume 配置
Spark 基础   
•  什么是 Apache Spark   
•  使用 Spark Shell   
•  RDDs( 可恢复的分布式数据集）   
•  Spark 里的函数式编程 Spark RDD   
•  RDD   
•  键值对 RDD   
•  MapReduce   
•  其他键值对 RDD 操作
编写和部署 Spark 应用   
•  Spark 应用对比 Spark Shell   
•  创建 SparkContext   
•  创建 Spark 应用（Scala 和 Java）   
•  运行 Spark 应用   
•  Spark 应用 WebUI   
•  配置 Spark 属性   
•  运行日志
Spark 的并行处理   
•  回顾：机群环境里的 Spark   
•  RDD 分区   
•  基于文件 RDD 的分区   
•  HDFS 和本地化数据   
•  执行并行操作   
•  执行阶段及任务
Spark 缓存和持久化   
•  RDD 演变   
•  缓存   
•  分布式持久化
Spark 数据处理的常见模式   
•  常见 Spark 应用案例   
•  迭代式算法   
•  图处理及分析   
•  机器学习   
•  例子：K－Means 预览：Spark SQL   
•  Spark SQL 和 SQL Context   
•  创建 DataFrames   
•  变更及查询 DataFrames   
•  保存 DataFrames   
•  Spark SQL 对比 Impala
Cloudera Administrator Training for Apache Hadoop(CCA131)  课程介绍
Apache Hadoop 介绍：
Hadoop 动机、基本概念、Hadoop 核心部件
Hadoop 机群安装：   
机群管理方案、Cloudera Manager 特性、Cloudera manager 安装、Hadoop (CDH) 安装
Hadoop 分布式文件系统 (HDFS)：   
HDFS 特性、读写文件、NameNode 内存考虑、HDFS 安全简介、HDFS Web UI、使用 HDFS Shell
第二天
YARN 上的 MapReduce 和 Spark：   
计算平台在 Hadoop 里扮演的角色、YARN：机群资源管理器、MapReduce 概念、Apache Spark 概念、Yarn 上的计算平台、YARN Web UI 及 Shell、YARN 应用运行日志
Hadoop 配置及服务运行日志：   
Cloudera Manager 配置管理机制、定位配置参数及进行配置变更、管理角色实例及添加服务、配置 HDFS 服务务、配置 Hadoop 服务运行日志、配置 YARN 服务
向 HDFS 导入数据：   
使用 Flume 从外部数据源实时导入数据、使用 Sqoop 从关系数据库导入数据、REST 接口、导入数据的最佳实践
第三天
Hadoop 机群规划：   
规划考虑因素、硬件选择、虚拟化选项、网络因素、节点配置
Hive，Impala 及 Pig 的安装及配置：   
Hive、Impala、Pig
Hadoop 客户端及 Hue：   
什么是 Hadoop 客户端、安装及配置 Hadoop 客户端、安装及配置 Hue、使用 Hue 进行身份验证及授权
第四天
机群高级配置：   
高级配置参数、Hadoop 端口配置、HDFS 机柜感知配置、HDFS 高可靠性配置
Hadoop 安全：   
Hadoop 安全的重要性、Hadoop 安全性概念、Kerberos 简介、使用 Kerberos 保护 Hadoop 机群、其他安全特性
资源管理：   
使用静态服务池配置 Linux cgroup、公平调度器、配置动态资源池、YARN 内存及 CPU 设置、Impala 查询调度
第五天
机群维护：   
检查 HDFS 状态、机群间复制数据、添加／移除机群节点、机群数据负载平衡、目录快照、机群升级
机群监控及排错：   
Cloudera Manager 监控特性、监控 Hadoop 机群、Hadoop 机群排错、常见配置不当问题
- 原文地址：168大数据 >> http://www.bi168.cn/thread-17597-1-1.html
