## 基础知识

### 语言

### Go语言
 
  - 内存管理方式
     - mHeadp->mCentral->mSpan->mObject
     - https://zhuanlan.zhihu.com/p/59125443
  - 协程调度模型GPM：
     - https://studygolang.com/articles/20991
     - https://segmentfault.com/a/1190000016824319
  - channel原理
  - sync包
  - strings包
  - map扩容机制：
     - https://zhuanlan.zhihu.com/p/66676224
  - go垃圾回收
     - https://zhuanlan.zhihu.com/p/82921000
     - https://zhuanlan.zhihu.com/p/74853110
  - go语言新特性：
     - https://studygolang.com/articles/26529?fr=sidebar
      
### php
 
  - 字符串操作函数
   - strlen
   - explode
   - implode
   - substr
   - trim
   - 字符串遍历
   
- 数组函数：
  - 二维数组
  - array_fill ( int $start_index , int $num , mixed $value ) : array
  - array_pop ( array &$array ) : mixed
  - array_push ( array &$array , mixed $value1 [, mixed $... ] ) : int
  - ksort ( array &$array [, int $sort_flags = SORT_REGULAR ] ) : bool
  - usort ( array &$array , callable $value_compare_func ) : bool
  - array_shift ( array &$array ) : mixed
  - array_unshift()
- array实现原理
- php请求处理流程
- php如何实现弱类型
    
     
 
### 数据结构与算法
 - 树
     - 前序/中序/后序遍历(递归/非递归)
     - 树高度
     - 深度优先遍历
     - 广度优先遍历
 - 图
     - 最短路径
     - 最小生成树
 - 排序算法
     - 快排
     - 归并排序
     - 冒泡排序
     - 堆排序
- 查找
     - 二分查找
     - KMP算法

### 计算机操作系统
  - CPU管理
  - 内存管理
  - 进程管理
  - 存储器管理
  - 设备管理


### 计算机网络
 - ISO七层模型
 - TCP/IP
     - 滑动窗口
     - 拥塞控制
     - 三次握手四次挥手
     - TCP报文结构
     - 粘包
     - tcp/udp区别
 - Https
     - Http报文结构
     - 常用状态码
     - cookie/session
     - https原理
     - http2特性
     
### 数据库
 - 事务隔离级别
 - 索引原理
 - MVCC原理

### redis
 - 缓存与数据一致性
 - AoF和RDB的区别
 - 主从同步原理：
   - https://www.jianshu.com/p/5147a6825322
 - psync
 - 哨兵和集群模式的区别：
   - 哨兵模式解决高可用故障发现与故障转移。集群则是实现分区扩展内存
 - redis新特性
   - 多线程读取+解析命令 
 

### 设计题
  - LRU缓存算法
  - 单例模式
  - **线程池**
  - 两个线程交替打印字符串
  - 连接池
  
### 设计模式
  - 职责链模式
  - 命令模式
  - 桥接模式
  - 单例模式
  - 简单工厂
  

### 容器化技术
 
 - docker原理
	 - namespace
	 - cgroup
 - k8s组件及其作用
    - master
	    - api-server
	    - controller-manager
	    - scheduler
   - node
      - kubelet
      - kube-proxy
   - etcd
   
  - k8s资源类型:pod/service/deployment/replicaController/Replica Set
  - k8s网络模式
  
  ### 微服务
  - 什么是微服务
  - 微服务分拆原则
  
  ### 分布式
  - 两阶段提交
  - TCC
  - 领域驱动设计
  - 分布式数据一致性
