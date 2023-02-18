# Mvc-Frame
spring boot MVC架构项目脚手架

### 项目子模块
+ Mvc-start   提供主启动类、yml配置文件、config配置类
+ Mvc-web     提供Controller接口，AOP
+ Mvc-service 定义项目使用的Service接口以及相关实体类
+ Mvc-core    提供项目Service接口实现类、定时任务、事件的订阅和发布
+ Mvc-manage 提供项目所用的Manager层接口和实现类，封装通用操作，若项目无添加Manager层需求，可删除
+ Mvc-storage 提供数据库存储服务，Mybatis/String Data Jpa
+ Mvc-common  提供通用返回对象、常量、枚举类、工具类、拦截器、自定义异常
+ Mvc-rpc     提供OpenFeign远程调用、熔断降级
+ Mvc-redis   提供redis配置类、redis工具类封装

### 项目使用技术
+ Spring Boot 2.78
+ Spring Cloud组件
+ Mysql 8.0.31
+ Mybatis-Plus
+ Redis 6.6
+ Redisson
+ Swagger2
+ Nacos
+ Kafka
+ XXL_Job