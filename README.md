# springbootstart
springboot 必知必会  原理测试


## 使用流程

* 加依赖   是类库 还是有starter 支持   dep + tab 键
> 官方的依赖 spring-boot-starter-

> 非官方的依赖 xxxx-spring-boot-starter

* 写注解 


* 写配置


## Spring Boot Actuator 应用监控

* /actuator/health : 健康检查  资源检查
* /actuator/info : 描述信息
* /actuator/configprops : 配置信息
* /actuator/metrics : 指标


## spring boot 配置管理

* "*" 在yml中的配置
* 配置的顺序

> 配置管理：

* 配置文件
* 环境变量   java -jar XXX.jar --ENV=xxx
* 外部配置文件   另外一份application.yml  在配置文件的同目录 下启动  比内部的配置文件高
* 命令行参数   在启动时指定 application.yml 内的参数  --server.port=8080

保持简单

## profile

不同的环境使用不同的配置