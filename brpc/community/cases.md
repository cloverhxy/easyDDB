# brpc的应用案例集合

## what is this
这里列出brpc在各个企业中的落地场景，包括企业名称，应用项目作用，集群规模和QPS统计，使用的版本信息等

## Why this
列出各个案例，一来方便用户进行参考，了解brpc可以用在哪些场景下；
二来方便社区开发者统计brpc的版本，规模等情况

# Case List
## 落地case的sample （如果有多个场景，建议分开）
* 公司名称： xxx公司
* 落地项目： 例如app的个性化推荐系统的预测服务
* 集群规模： 例如100台
* QPS： 例如峰值1000万， 均值100万
* 使用版本： 例如社区版本0.9.7
* 信息提供者：某某

## brpc在 百度的落地情况
* 公司名称： 百度
* 落地项目： 基础架构(分布式计算、存储、数据库等)，业务系统（Feed、凤巢、地图等）
* 集群规模： 4000多个活跃模块，600w以上实例
* 使用版本： baidu内部版本
* 信息提供者：wwbmmm

## brpc在维沃的落地情况
* 公司名称： 维沃（vivo）
* 落地项目： 在线推荐系统
* 使用版本： 社区版本0.9.7
* 信息提供者：guodongxiaren

## brpc在爱奇艺的落地情况
* 公司名称： 爱奇艺（iqiyi）
* 落地项目： 广告、推荐、搜索
* 使用版本： 基于社区版本定制
* 集群规模： 3000+台机器(广告)
* 信息提供者：cdjingit

## brpc在第四范式的落地情况
* 公司名称： 第四范式（4paradigm）
* 落地项目： 风控、推荐、智能运维等
* 使用版本： 基于社区版本定制
* 信息提供者：dl239

## brpc在 小红书的落地情况
* 公司名称： 小红书
* 落地项目： 推荐系统，基础架构(存储等)
* 集群规模： 1w以上实例(推荐)
* 使用版本： 基于社区版本定制
* 信息提供者：lzfhust

## brpc在作业帮的落地情况
* 公司名称： 作业帮
* 落地项目： 长连接IM，消息分发系统
* 集群规模： 2000+核
* 使用版本： 基于0.9.7定制
* 信息提供者：xdh0817

## brpc在欢聚时代的落地情况
* 公司名称： 欢聚时代
* 落地项目： 推荐、直播
* 使用版本： 基于社区版本定制
* 信息提供者：chenBright

## brpc 在 Apache Doris 中的应用
* 落地项目：Apache Doris
* 使用版本：1.2.0
* 使用情况：Apache Doris 作为一款 MPP 分析型数据库，其内部节点间使用 Apache Brpc 作为主要 RPC 框架。Brpc 为 Doris 提供了稳定易用的高性能通信机制。并且 BRPC 提供的 bthread，bvar 等基础库，以及各种性能调试工具，也极大的方便了 Doris 的开发和调试工作。
* 信息提供者：morningman