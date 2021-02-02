# S1 基础篇 （已完结）

### 1.1 为什么要学习 Apache Flink？

[PPT点我](https://files.alicdn.com/tpsservice/53de65050b468fc6d338fbaff799828a.pdf)

- 课程介绍：为什么会开设系列课程？
- Apache Flink：定义/架构/原理
- 高效学习：学前准备以及学习方法

[视频回放点我](https://www.bilibili.com/video/av45615081/)

[1&2课文章](https://mp.weixin.qq.com/s/oBmRhRA-52CLRLXp6sZwEw)

 讲师：陈守元（阿里巴巴高级产品专家）

### 1.2 Flink基本概念

[PPT点我](https://files.alicdn.com/tpsservice/b55f732fbc32522ca5394544f3834530.pdf)

- 何谓“有状态流式处理”？
- 有状态流式处理的挑战
  - 状态容错：分散式状态容错、分散式快照
  - 状态维护：状态后端
  - Event-time处理：Watermarks
  - 状态保存与迁移：保存点savepoint
- 总结

[视频回放点我](https://www.bilibili.com/video/av46277503/)

[1&2课文章](https://mp.weixin.qq.com/s/oBmRhRA-52CLRLXp6sZwEw)

讲师：戴资力（Apache Flink PMC) 

### 1.3 Flink 安装部署、环境配置及运行应用程序

[PPT点我](https://files.alicdn.com/tpsservice/4824447b829149c86bedd19424d05915.pdf)

- Flink开发环境部署和配置
- 运行Flink应用

[视频回放点我](https://www.bilibili.com/video/av46986124/)

[第三课文章](https://mp.weixin.qq.com/s/noD2Jv6m-somEMtjWTJh3w)

### 1.4 DataStream API编程
[PPT点我](https://files.alicdn.com/tpsservice/38bf5c75c7491323b4b99101a2fab65c.pdf) 

- 分布式流处理基础
- Flink DataStream API概览
- 其他问题：物理分组、类型系统
- 源码简析

[视频回放点我](https://www.bilibili.com/video/av47970985/)

[第四课文章](https://mp.weixin.qq.com/s/nLHjYUCx2mOGBSFS4_uu_g)

讲师：崔星灿（Apache Flink Committer)

### 1.5 客户端操作
[PPT点我](https://files.alicdn.com/tpsservice/a8d224d6a3b8b82d03aa84e370c008cc.pdf)

- Flink命令行

[视频回放点我](https://www.bilibili.com/video/av47600600/)

[第五课文章](https://mp.weixin.qq.com/s/KfuAZv2G0682NNzHv0iFfQ)

讲师：周凯波（阿里巴巴技术专家）

### 1.6 Window & Time
[PPT点我](https://files.alicdn.com/tpsservice/5a77d1eaf0fda97b512762103c4cbd91.pdf)

- Window & Time
- Window API使用
- Window内部实现

[视频回放点我](https://www.bilibili.com/video/av49401210/) 

[第六课文章](https://mp.weixin.qq.com/s/43N3W9rQ2HEHIyBM1jh4Lw)

讲师：邱从贤（阿里巴巴高级开发工程师）

### 1.7 状态管理与容错机制 
[PPT点我](https://files.alicdn.com/tpsservice/1b9f5f0bda10883dce78496e6a5d648a.pdf)

- 状态管理的基本概念
  - 什么是状态
  - 为什么要管理状态
  - 理想的状态管理
- 状态的类型与使用示例
  - Managed State & Raw State
  - Keyed State & Operator State
  - Keyed State使用示例
- 容错机制与故障恢复
  - 状态如何保存及恢复：Checkpoint、Savepoint
  - 可选的状态存储方式：MemoryStateBackend、FsStateBackend、RocksDBStateBackend

[视频回放点我](https://www.bilibili.com/video/av49736102/) 

[第七课文章](https://mp.weixin.qq.com/s/1ssipS4vseDf1cgXQHxBRw)

讲师：孙梦瑶（美团点评研发工程师)

### 1.8 Flink Table API 编程 

[PPT点我](https://files.alicdn.com/tpsservice/a44825ebca091345481dc2ddbb789d1d.pdf)

- 什么是Table API
  - Flink API总览
  - Table API的特性
- Table API编程：Columns Operation & Function、Row-based operation
- Table API动态

[视频回放点我](https://www.bilibili.com/video/av50460716/) 

[第八课文章](https://mp.weixin.qq.com/s/B2-WT3gSui4ylmWK92aQng)

讲师：程鹤群（Apache Flink Contributor)

### 1.9 Flink SQL 编程
[PPT点我](https://files.alicdn.com/tpsservice/3d4b0eaf1d24414ecf76f5e597b6c276.pdf)

- Flink SQL介绍：Window Aggregation、Group Aggregation

[视频回放点我](https://www.bilibili.com/video/av50871853/) 

[第九课文章](https://mp.weixin.qq.com/s/QUaJJtB5A9vyAB3d_Vg6bA)

讲师：伍翀（Apache Flink Committer)

# S2 进阶篇（已完结）
### 2.1 Flink Runtime 核心机制剖析 
[PPT](https://files.alicdn.com/tpsservice/7bb8f513c765b97ab65401a1b78c8cb8.pdf)

- 整体架构：Runtime层整体架构
- 资源管理与作业调度：Slot管理与划分
- 错误恢复：Task Failover、Master Failover
- 未来展望

[视频回放](https://www.bilibili.com/video/av52394455/) 

[第一课文章](https://mp.weixin.qq.com/s/TBzzGTNFTzVLjFQdzz-LuQ)

讲师：高赟（Apache Flink Contributor，阿里巴巴高级开发工程师)

### 2.2 Flink Time 深度解析
[PPT](https://files.alicdn.com/tpsservice/a555d1924a5af65e30abbf7ed426129a.pdf)

- Flink时间语义
- Event Time和Watermark
- Table中的时间
- 深入思考：数据or元数据、干涉Watermark传播、统一EventTime和ProcTime处理

[视频回放](https://www.bilibili.com/video/av53193640/) 

[第二课文章](https://mp.weixin.qq.com/s/2VMsTvCW9eshEnB-Ak_cIw)

讲师：崔星灿（Apache Flink Committer，加拿大约克大学博士后)

### 2.3 Flink Checkpoint-轻量级分布式快照

[PPT](https://files.alicdn.com/tpsservice/58f47c9d098379537de5ba7f190eac8c.pdf)

- 总览：Checkpoint与state
- 什么是state：Keyed State、Operator State
- 如何在Flink中使用state
- Checkpoint的执行机制：state的存储

[视频回放](https://www.bilibili.com/video/av54074405/) 

[第三课文章](https://mp.weixin.qq.com/s/QCVWSYZDeQQJjjuQtINZ4A)

讲师：唐云（Apache Flink Contributor，阿里巴巴高级开发工程师)


# Flink理论

## 一、简介

## 二、快速上手
### 1. 批处理wordcount
### 2. 流处理wordcount

## 三、部署
### 1. 基本配置和启动集群
### 2. 提交任务和测试
### 3. 命令行操作及其他部署方式

## 四、运行架构
### 1. 运行时的组件和基本原理
### 2. Slot和并行度
### 3. 数据流和执行图
### 4. 任务调度控制

## 五、Flink DataStream API
### 1. 环境和简单source
### 2. Kafka Source
### 3. 自定义Source
### 4. 基本转换算子
### 5. 聚合算子
### 6. 多流转换算子
### 7. UDF函数
### 8. Kafka Sink
### 9. Redis Sink
### 10. ES Sink
### 11. JDBC 自定义Sink

## 六、Flink Window API
### 1. 概念和类型
### 2. API

## 七、Flink时间语义

## 八、Watermark

## 九、Flink窗口操作
### 1. 简单测试
### 2. 事件时间测试
### 3. Window起始点

## 十、Flink底层API
### 1. Process Function
### 2. Process Function编程示例
### 3. 侧输出流

## 十一、Flink状态管理
### 1. 算子状态和键控状态
### 2. 状态后端

## 十二、Flink状态编程

## 十三、Flink容错机制
### 1. 检查点
### 2. 检查点算法
### 3. 检查点配置

## 十四、Flink状态一致性
### 1. 状态一致性
### 2. 端到端(end-to-end)状态一致性
### 3. Flink+Kafka端到端状态一致性的保证


# Table API 和 Flink SQL

## 一、简介
## 二、表环境定义
## 三、读取文件创建表
## 四、读取kafka数据创建表
## 五、表的查询转换
## 六、表和流相互转换
## 七、输出到文件
## 八、更新模式
## 九、数据管道测试
## 十、写入数据到其他外部系统
## 十一、时间语义和时间属性的定义
## 十二、Group Windows
## 十三、Over Windows
## 十四、Flink SQL中的窗口实现
## 十五、系统内置函数
## 十六、自定义标量函数
## 十七、自定义表函数
## 十八、自定义聚合函数
## 十九、自定义表聚合函数
