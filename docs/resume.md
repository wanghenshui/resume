 <center>
     <h1>王全伟</h1>
 </center>

## 个人信息 

* 性 别：男&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; 
* 手 机：(+86) 188-4418-9533 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;  邮 箱：wanghenshui@qq.com

## 工作及教育经历

* 腾讯科技有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;2020.10~至今&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; TEG技术工程事业群-云架构平台部
* 华为技术有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;2018.10~2020.09&emsp;&emsp;&emsp;&emsp;&emsp; CloudBU数据库服务产品部
* 海能达科技有限公司&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;2016.07~2018.09&emsp;&emsp;&emsp;&emsp;&emsp; 系统软件设计开发部
* 吉林大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;2012.09~2016.07&emsp;&emsp;&emsp;&emsp;&emsp; 电子信息工程系-本科  

## 专业技能

* 熟练C++，Go会一点
* 数据库方向: 熟悉RocksDB, Redis, MySql, 了解MongoDB


## 项目经历

1. 腾讯 - 云原生分布式多模型KV存储
    * 基于多种引擎 rocksdb/fasterkv编码KV实现存储能力
    * 基于multi-raft的多租户模式，平摊成本
    * 支持多种存储模型，简单KV，redis类型，复杂key-key-row，时序，宽表，图等等
    * 探索更多的编码模型,以及新技术io_uring/coroutine(c++20)
    * PB级数据，P99<10ms,成功率 > 99.9%

2. 腾讯 - 数据库导入平台建设
    * 基于多种引擎 rocksdb/fasterkv，接入多种数据平台，实现离线构建-导入数据库上线
    * 优化调度系统，CPU利用率内存利用率 > 50%
    * 每月上万次导入。成功率>99.5%

3. 华为 - CloudBU - GaussDB for Redis 原型开发
    * 多模型NoSQL数据库GaussDB redis接口开发。适配上云
    * 适配分布式文件存储，基于此实现秒级扩缩容/备份

4. 华为 - CloudBU - MongoDB 基于rocksdb的分布式事务原型开发
    * RocksDB引入时间戳能力，支持基于时间戳的compact/版本
    * 支持多shard基于rocksdb的乐观事务(OCC)

5. 海能达 - 系统软件设计开发部 - 核心网/基站开发项目
    * 维护对讲机-基站-核心网调度功能稳定以及添加新功能
    * 涉及到多种平台(ARM微型机/x86微型机)的功能开发以及移植工作
    * 千万级别关联数据，涉及到网络架构拆分支持大规模查询/cache组件使用(redis) 提高响应以及可用性
    * 项目对接，响应/定位现网问题


## 开源社区相关
* blog 地址 https://wanghenshui.github.io/
* github ID wanghenshui 可以在主页查看开源贡献
* 弄了个C++相关的信息站/公众号 搜CPP每周推送，看到简历的朋友加加关注