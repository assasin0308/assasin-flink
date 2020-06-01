# assasin-flink
### 1. 应用场景与架构模型

```json
# 场景: 
# 1. 实时数据计算;数据实时采集,实时计算和下游发送
# 2. 实时数据仓和ETL(Extract-Transform-Load目的是将业务系统的数据经过抽取,清晰和转换之后加载到数据仓库的过程);
# Flink在实时数仓和ETL中有天然的优势:
	# 状态管理:实时数仓会进行很多的聚合计算,这些都需要对状态进行访问和管理,Flink支持强大的状态管理
	# 丰富法人API: Flink提供极为丰富的API,包括stream API,Table API 和Flink SQL
	# 生态完善: 实时数仓的用途广泛,flink支持多种存储(HDFS,ES等)
	# 批流一体: flink已将流计算与批计算的API进行统一
# 3. 事件驱动型应用;
	# 高效的状态管理，Flink 自带的 State Backend 可以很好的存储中间状态信息；
	# 丰富的窗口支持，Flink 支持包含滚动窗口、滑动窗口及其他窗口；
	# 多种时间语义，Flink 支持 Event Time、Processing Time 和 Ingestion Time；
	# 不同级别的容错，Flink 支持 At Least Once 或 Exactly Once 容错级别。
# Flink分层模型

# SQL 		                 ------ High-level Language
# Table API	                 ------ Declarative DSL
# DataStream/DataSet Api     ------ Core APIs
# Stateful Stream Processing ------ Low-level building block(streams,state,[event] time)

# Flink的基础构建模块
#  流 (Stream)
#  转换 (Transformations)
# 每一个数据流起始于一个或多个source,并终止于一个或多个sink.

# 窗口和时间是Flink的核心概念之一,在实际生产环境中,对数据流上的聚合需要由窗口来划定范围.如"计算过去的5分钟"或者 "最后100个元素的和"等,flink支持如滑动窗口,滚动窗口,会话窗口等多种窗口模型.此外Flink自身还支持有状态的算子计算,容错机制,Checkpoint,Exactly-once语义等更高级特性.


```

### 2. WordCount与SQL实现

```json
# 环境搭建:
# https://maven.apache.org/download.cgi
# JDK1.8及以上
# git
# https://github.com/apache/flink

curl https://flink.apache.org/q/quikstart.sh | bash -s 1.10.0

```

### 3. 

```json

```

### 4.  

```json

```

### 5. 

```json

```

### 6. 

```json

```

### 7. 

```json

```

### 8. 

```json

```

### 9. 

```json

```

### 10. 

```json

```

### 11. 

```json

```

### 12. 

```json

```

### 13. 

```json

```

### 14. 

```json

```

### 15. 

```json

```

### 16. 

```json

```

### 17.  

```json

```

### 18. 

```json

```

### 19.  

```json

```

### 20. 

```json

```

### 21.

```json

```

### 22.

```json

```

### 23.

```json

```

### 24.

```json

```

### 25.

```json

```

### 26.

```json

```

### 27.

```json

```

### 28.

```json

```

### 29.

```json

```

### 30.

```json

```

### 31.

```json

```

### 32.

```json

```

### 33.

```json

```

### 34.

```json

```

### 35.

```json

```

### 36.

```json

```

### 37.

```json

```

### 38.

```json

```

### 39.

```json

```

### 40.

```json

```

### 41.

```json

```

### 42.

```json

```

### 43.

```json

```

### 44.

```json

```

### 45.

```json

```

### 46.

```json

```

### 47.

```json

```

### 48.

```json

```

### 49.

```json

```

### 50.

```json

```



