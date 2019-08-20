<h1 align="center">mini-springcloud</h1>

## Demo project for Spring Cloud ##

### Usage
---
一、目录结构
```
├── config-client            # 远程配置 客户端
├── config-server            # 远程配置 服务端
├── config                   # 远程配置 存放配置文件
├── consumer                 # 服务消费者
├── eureka-client            # 服务提供者
├── eureka-server            # 注册中心
├── feign                    # 声明式接口调用（测试熔断）
├── hystrix                  # 容错机制
├── native-config-client     # 本地配置 客户端
├── native-config-server     # 本地配置 服务端
├── rest-template            # REST服务组件
├── ribbon                   # 负载均衡
├── zipkin-client            # 服务跟踪 客户端
├── zipkin                   # 服务跟踪 服务端
└── zuul                     # 服务网关
```
二、使用说明 <br>

[前言](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#单服务架构存在的问题) <br>
[eureka-server 注册中心 代码实现](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Eureka-Server代码实现（注册中心）) <br>
[eureka-client 服务提供者 代码实现](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Eureka-Client-代码实现) <br>
[rest-template（REST服务组件）](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#RestTemplate-的使用) <br>
[consumer 服务消费者 代码实现](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#服务消费者-consumer) <br>
[zuul 服务网关](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#服务网关) <br>
[ribbon 负载均衡](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Ribbon-负载均衡) <br>
[feign 声明式接口调用](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Feign) <br>
[hystrix 容错机制](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Hystrix-容错机制) <br>
[native-config 本地配置](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Spring-Cloud-配置中心) <br>
[Spring Cloud Config 远程配置](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#Spring-Cloud-Config-远程配置) <br>
[zipkin 服务跟踪](https://cmini777.gitee.io/2019/08/17/Spring-Cloud%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E5%AE%9E%E6%88%98/#服务跟踪) <br>

-----

## Thanks

感谢   [myspringclouddemo](https://github.com/southwind9801/myspringclouddemo) 

