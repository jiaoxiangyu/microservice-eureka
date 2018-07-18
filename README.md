# 微服务-服务发现组件（Eureka）
---

**简介：** 

microservice-eureka-demo

服务提供者：microservice-simple-provider-user（用户个人信息）

服务消费者：microservice-simple-consumer-movie （购电影票，调用个人信息）

服务发现组件：microservice-discovery-eureka


依据：该demo是学习《Spring Cloud与Docker微服务架构实战》测试，建议阅读这本书，我这里就不重复介绍代码了

1、文件singleEurekaServer：一个Eureka Server

2、文件doubleEurekaServers：Eureka Server集群（两个Eureka Server），数据复制共享，防止宕机

3、文件authenticatingEurekaServers：添加用户认证的Eureka Server集群，测试失败，无法注册服务，没找到原因，用F版springcloud不知道怎么配置用户认证

